---
layout: page
title: Real-time Sequence Clustering
description: An interpretable algorithm to cluster sequences in real-time 
img: assets/img/projects/seqclustering.png
importance: 3
category: Completed
related_publications: true
---


**Description:**

In cybersecurity, malicious behavior is known to evolve rapidly to evade detection. 
For instance, network traffic must be continuously monitored to accurately characterize malware capabilities at any given time. 


This creates the need for a real-time sequence clustering approach that can handle evolving 
data distributions (i.e., due to concept drift). Existing real-time clustering algorithms have limited support for sequential data. 
Besides, a highly efficient algorithm is required to cluster the large volumes of network traffic required for real-time behavioral analytics. 
Furthermore, the algorithms that support sequential data do not provide interpretability, which is a problem in itself since the 
analysts need to be able to understand the evolving behaviors captured by a cluster. There is currently no way to cluster large sequential datasets 
in real-time while supporting interpretability and concept drift. 

In this project, we aim to develop the first interpretable clustering algorithm that efficiently clusters sequences in real-time {% cite nadeem2022secleds %}. 
Specifically, we aim to create a linear and real-time version of the k-medoids algorithm. This algorithm should be able to summarize network traffic, 
i.e., represent important concepts using its k medoids. We will then investigate whether such an algorithm improves the quality of malware capability assessment 
compared to standard approaches.

**Code repo:** [SECLEDS](https://github.com/tudelft-cda-lab/SECLEDS) [![SECLEDS](https://img.shields.io/github/stars/tudelft-cda-lab/SECLEDS?style=social)](https://github.com/tudelft-cda-lab/SECLEDS)
