---
title: "Taxonomy Learning"
layout: archive
excerpt: "<img src='/images/research/Taxonomy_ex2.png' alt='Taxonomy Learning'>"
collection: research
order_number: 1
header: 
---

In this research, I have developed TaxoFinder (2016) that is an algorithm for automatically inducing a taxonomy of important concepts from a text corpus. It takes the 3 main steps:
- First, TaxoFinder identifies concepts from the corpus using a concept extractor, [CFinder](/publication/CFinder_2014). The output of this step includes the ranked list of concepts according to their domain relevance. 
- Second, TaxoFinder builds a graph, named CGraph, which represents how concepts are associated together based on their co-occurrences. Using the sentence similarity and sentence distance measures, the strength of each association is quantified. 
- Lastly, a taxonomy is induced from the CGraph using a graph analytic algorithm. 

In 2020, a subject term taxonomy inducing algorithm (named [SubjectTracker](https://github.com/Yongbinkang/SubjectTracker)) was developed, in order to promote information retrieval tasks such as indexing, cataloging and searching of digital documents. Subject terms are used to index digital documents.

<style>
img {
  max-width: 60%;
  height: auto;
}
</style>


### Architecture of SubjectTracker: 
![](/images/research/subject_tracker.png)

### Research Objectives:
 - Develop AI techniques to automatically build an insightful subject term taxonomy that reflects the semantics ofsubject terms used to index (or categorise) policy research publications in APO
 - Improve the comprehensiveness of the semantics of policy research publications by accurately indexing them with the subject terms via advanced NLP techniques

### Achievements:
 - AI-based subject term taxonomy building model, SubjectTracker, is developed. Given the existing pool of manually-defined subject terms used to index policy research publications in [APO](https://apo.org.au/), SubjectTracker can automatically build a subject term taxonomy by identifying their mutual information for indexing and
 their semantic relatedness.
 - For each subject term, SubjectTracker can recommend its synonyms from Wikipedia titles to enrich the coverage andunderstanding of the subject term.
 - SubjectTracker also can merge (or group) insignificant subject terms with significant subject terms based on a semanticsimilarity measure between subject terms.

### Social Benefits:
 - SubjectTracker can be used for creating a semantic taxonomy of (or metadata) terms, used for indexing text data, in the controlled vocabulary in a domain. 
- SubjectTracker can be used to enhance the existing taxonomy to redefine/improve the semantic relatedness of such terms with morecondensed and meaningful controlled terms. 
 - The learned taxonomy can be used as the key to facilitating information retrieval, knowledge searching and classification of the policy research publications.

## Article
<b>Yong-Bin Kang</b>, Jihoon Woo, Les Kneebone, Timos Sellis, Methodology for refining subject terms and supporting subject indexing with taxonomy: A case study of the APO digital repository, Decision Support Systems, Volume 146, 2021, 113542, ISSN 0167-9236, https://doi.org/10.1016/j.dss.2021.113542.

> In digital repositories, it is crucial to refine existing subject terms and exploit a taxonomy with subject terms, in order to promote information retrieval tasks such as indexing, cataloging and searching of digital documents.
In this paper, we address how to refine an existing set of subject terms, often containing irrelevant ones or creating noise, that are used to index digital documents. Further, we present how to automatically induce a subject term taxonomy to capture and utilise the semantic relations among subject terms. Most related works have little studied these problems, focusing mostly on creating subject terms or building a taxonomy of key terms from text documents. 
We propose a methodology for refining an existing set of subject terms in a  digital repository by identifying their semantics, as well as inducing a taxonomy with subject terms by analysing their mutual usages, maximising their semantic relatedness. Then, we present a case study using the (Analysis \& Policy Observatory) APO digital repository to analyse the proposed methodology and demonstrate its applicability. 
Further, to validate the generalisability of the proposed taxonomy inducing method, we evaluate it using a gold-standard taxonomy in life sciences, Medical Subject Headings (MeSH), in comparison with the state–of-the-art taxonomy inducing method, TaxoFinder. Our evaluation shows that our methodology has a high potential for refining an existing set of subject terms and capturing their semantic relationships by inducing a subject term taxonomy.

[Paper Download](/files/research/subject_taxonomy_dss_2021.pdf){: .btn--research} [DOI](https://doi.org/10.1016/j.dss.2021.113542){: .btn--research} [GitHub Repo](https://github.com/Yongbinkang/SubjectTracker){: .btn--research}

## Article
<b>Yong-Bin Kang</b>, Pari Delir Haghighi, and Frada Burstein, TaxoFinder: A Graph-Based Approach for Taxonomy Learning, IEEE Transactions on Knowledge and Data Engineering, vol. 28, no. 2, pp. 524-536, 1 Feb. 2016, doi: 10.1109/TKDE.2015.2475759.

> Taxonomy learning is an important task for knowledge acquisition, sharing, and classification as well as application development and utilization in various domains. To reduce human effort to build a taxonomy from scratch and improve the quality of the learned taxonomy, we propose a new taxonomy learning approach, named TaxoFinder. TaxoFinder takes three steps to automatically build a taxonomy. First, it identifies domain-specific concepts from a domain text corpus. Second, it builds a graph representing how such concepts are associated together based on their co-occurrences. As the key method in TaxoFinder, we propose a method for measuring associative strengths among the concepts, which quantify how strongly they are associated in the graph, using similarities between sentences and spatial distances between sentences. Lastly, TaxoFinder induces a taxonomy from the graph using a graph analytic algorithm. TaxoFinder aims to build a taxonomy in such a way that it maximizes the overall associative strengths among the concepts in the graph to build a taxonomy. We evaluate TaxoFinder using gold-standard evaluation on three different domains: emergency management for mass gatherings, autism research, and disease domains. In our evaluation, we compare TaxoFinder with a state-of-the-art subsumption method and show that TaxoFinder is an effective approach significantly outperforming the subsumption method.

[Paper Download](/files/research/taxofinder.pdf){: .btn--research} [DOI](https://ieeexplore.ieee.org/abstract/document/7236916){: .btn--research} 