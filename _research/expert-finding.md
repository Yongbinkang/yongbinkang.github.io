---
title: "Expert Finding"
layout: archive
excerpt: "<img src='/images/research/FLExR.png' alt='Expert finding'>"
collection: research
order_number: 1
header: 
---

<style>
img {
  max-width: 90%;
  height: auto;
}
</style>

### Architecture of ExpFinder: 
- Step 1:  Estimate the weights of experts and documents given topics in nVSM.
- Step 2: Construct Expert Collaboration Graph.
- Step 3: Reinforce expert weights using the μCO-HITS algorithm proposed in the paper below.

![](/images/research/expfinder_arch.png)

### Research Objectives:
 - Identify right experts and their expertise in a given organisation from the text evidence of expert knowledge (e.g. patents, scientific publications).
 - Accelerate research development and the rapid formation of disciplinary teams to respond to new research opportunities by identifying experts.

### Achievements:
 - A new expert finding model, ExpFinder, is developed. Its key idea is the integration of two knowledge facets: (1) semantic analysis of text evidence of expert knowledge using a document language model; and (2) an expert collaboration network.
 - ExpFinder can identify accurate experts with expertise in a domain, in which the  expertise is represented by a set of the keyphrases ranked according to their relevance to each expert. 

### Social Benefits:
 - ExpFinder is  designed to be domain-independent so that it can be applied to any domain  that  has experts and experts’ text-based evidence. This model can promote effective collaborations and making informed research decisions in academic and industry organisations, thereby accelerating scientific society and boosting productivity.

## Article
<b>Yong-Bin Kang</b>, Hung Du, Abdur Rahim Mohammad Forkan, Prem Prakash Jayaraman, Amir Aryani, Timos Sellis, ExpFinder: An Ensemble Expert Finding Model Integrating N-gram Vector Space Model and μCO-HITS, arXiv:2101.06821, 2021

> Finding an expert plays a crucial role in driving successful collaborations and speeding up high-quality research development and innovations. However, the rapid growth of scientific publications and digital expertise data makes identifying the right experts a challenging problem. Existing approaches for finding experts given a topic can be categorised into information retrieval techniques based on vector space models, document language models, and graph-based models. In this paper, we propose ExpFinder, a new ensemble model for expert finding, that integrates a novel N-gram vector space model, denoted as nVSM, and a graph-based model, denoted as μCO-HITS, that is a proposed variation of the CO-HITS algorithm. The key of nVSM is to exploit recent inverse document frequency weighting method for N-gram words, and ExpFinder incorporates nVSM into μCO-HITS to achieve expert finding. We comprehensively evaluate ExpFinder on four different datasets from the academic domains in comparison with six different expert finding models. The evaluation results show that ExpFinder is an highly effective model for expert finding, substantially outperforming all the compared models in 19% to 160.2%. 

[Paper Download](/files/research/Expertise_Retrieval_TKDE_2021.pdf){: .btn--research} [DOI](https://arxiv.org/abs/2101.06821){: .btn--research} [GitHub Repo](https://github.com/Yongbinkang/ExpFinder){: .btn--research}

## Article
Hung Du, <b>Yong-Bin Kang</b>, An open-source framework for ExpFinder integrating N-gram vector space model and μCO-HITS, Software Impacts, Volume 8, 2021, 100069, ISSN 2665-9638, https://doi.org/10.1016/j.simpa.2021.100069.

> Finding experts drives successful collaborations and high-quality product development in academic and research domains. To contribute to the expert finding research community, we have developed ExpFinder which is a novel ensemble model for expert finding by integrating an N-gram vector space model ($n$VSM) and a graph-based model (μCO-HITS). This paper provides descriptions of ExpFinder's architecture, key components, functionalities, and illustrative examples. ExpFinder is an effective and competitive model for expert finding, significantly outperforming a number of expert finding models.

[Paper Download](/files/research/ExpFinder__ElsevierSI_2021.pdf){: .btn--research} [DOI](https://doi.org/10.1016/j.simpa.2021.100069){: .btn--research} [GitHub Repo](https://github.com/SoftwareImpacts/SIMPAC-2021-18){: .btn--research}