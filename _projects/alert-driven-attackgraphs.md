---
layout: page
title: Attacker Strategy Discovery
description: Bridging the gap between alert management and attack graph generation
img: assets/img/projects/ags.png
importance: 2
category: Completed
related_publications: true
---


**Description:**

Practitioners in Security Operations Centers (SOC) struggle to keep up with the dramatic volumes of intrusion alerts. 
Once a network intrusion is detected, the process to identify and reverse engineer attacker strategies (attack campaigns) 
is largely manual and time-consuming. While existing alert correlation techniques reduce the volume of alerts to analyze, they do not 
show attack progression. Meanwhile, traditional attack graphs (AG) show attack progression, but rely heavily on expensive expert knowledge 
that is not always available, resulting in graphs that only show a static view of the network. Learning attack graphs from data is a longstanding 
open problemin cybersecurity and formal methods. It is challenging to discover sequential constraints within data while mitigating issues related to a 
state-space explosion. Existing efforts have so far managed to summarize alert datasets using sequential 
machine learning without explicitly extracting attack graphs. 

This project explores unsupervised sequence learning techniques to construct attack graphs directly from intrusion alerts as a way of bridging 
the gap between dynamic alert management and static attack graphs. This is a challenging task since intrusion alerts are typically highly imbalanced, 
and the alerts can appear in different contexts even if they have the same signatures. We aim to develop alert-driven attack graphs that are capable of 
compressing thousands of alerts, and can enable analysts to triage critical alerts only. We also aim to develop a dashboard for the alert-driven AGs 
that provides additional prioritization and querying capabilities to security analysts.
