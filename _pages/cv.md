---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.S. in Computer Science, VinUniversity, 2026 (Expected)

Work experience
======
* FPT.AI - FPT Smart Cloud: AI Engineer/Researcher Intern
  * Finetune open-source Vienamese LLMs (Vietnamese-Llama2-7B, VinaLlama-7B, Vistral-7B) using Low-Rank Adaptation for Dialogue State Tracking problem on ViWOZ dataset. 

* HysonLab: Research Assistant
  * Research on Graph-enhanced multimodal model for Design2Code. 
  * Research on Graph RAG for Document Queries, a collaborative project with Knovel Lab

Honors and Awards
======
* Second Prize in Vietnam Olympiad in Informatics, 2019
* Participate in Team Selection Test for Regional and International Olympiad in Informatics, 2019
* Second Prize in Vietnam Olympiad in Informatics, 2020
* Third Prize in The 2020 ICPC Asia Hanoi Regional Contest
* Best presentation team of SoICT's International Summer School in Modern Machine Learning, 2023

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Skills
======
* Programming Languages: Python, C/C++, Java
* Packages/Libraries: Pytorch, Pytorch-geometric, Transformers, Git, Langchain, Hunggingface
* Languages: Vietnamese, English

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->