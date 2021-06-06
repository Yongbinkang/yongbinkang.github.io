---
title: "Topic Trajectory Modeling"
layout: archive
excerpt: "<img src='/images/research/topic_tracker.png' alt='Topic Trajectory Model'>"
collection: research
order_number: 1
header: 
---

<style>
img {
  max-width: 70%;
  height: auto;
}
</style>

### Main Features of TopicTracker: 
- Use dynamic topic modeling to identify topics and their evolution over a time period. This provides precious insights into the dynamics of topics over time.
- Identify and visualise evolutionary pathway of dynamic topics as a series of evolutionary relationships between older topics and newer topics.

![](/images/research/topic_tracker.png)

### Research Objectives:
 - Identify technological trajectories and estimate the directions of technical changes to dynamic topics

### Achievements:
 - A novel topic identification framework, named Topic-Tracker, is developed.TopicTracker can discover evolutionary trajectories of dynamic topics over time by identifyingtheir transmission pathways over time and eventually create a evolution tree of dynamic topics. This tree reflects credibletechnological ancestry relationships of these topics based on their evolutionary strengths.
 - TopicTracker tackles these open questions: (1) How to formally define evolving evolutionary states of dynamic topicsover time? (2) How to formally define an evolutionary relationship between two dynamic topics?
- TopicTracker is using advanced dynamic topic modelling and text mining, exploiting the semantics of text words.

### Social Benefits:
 - TopicTrackeris designed to be generalisable, and thus it can be applied to any other domains where we desire to identifytopic trajectories from a large collection of text data. It can be usefully applied to automatically identify the prior art ofpatents which is currently relying on examiners.
 - TopicTracker can be utilised for (1) making informed decision on investments on future dominant technologies by governments or high-tech industries, (2) knowing world competitors for current technology or tools, and (3) understanding how technologies have emerged and thrived over time thus guiding credible future technology development directions.

## Article
<b>Yong-Bin Kang</b>, Timos Sellis, TopicTracker: A Platform for Topic Trajectory Identification and Visualisation, arXiv:2103.01432, 2021

> Topic trajectory information provides crucial insight into the dynamics of topics and their evolutionary relationships over a given time. Also, this information can help to improve our understanding on how new topics have emerged or formed through a sequential or interrelated events of emergence, modification and integration of prior topics. Nevertheless, the implementation of the existing methods for topic trajectory identification is rarely available as usable software. In this paper, we present TopicTracker, a platform for topic trajectory identification and visualisation. The key of TopicTracker is that it can represent the three facets of information together, given two kinds of input: a time-stamped topic profile consisting of the set of the underlying topics over time, and the evolution strength matrix among them: evolutionary pathways of dynamic topics, evolution states of the topics, and topic importance. TopicTracker can also help the user to speed up the development of different models for topic trajectory identification more easily by tailoring to to specific related areas of interest.
TopicTracker is a publicly available software implemented using the R software. 

[Paper Download](/files/research/TopicTracker_SoftwareX_2021.pdf){: .btn--research} [DOI](https://arxiv.org/pdf/2103.01432.pdf){: .btn--research} [GitHub Repo](https://github.com/Yongbinkang/SubjectTracker){: .btn--research}
