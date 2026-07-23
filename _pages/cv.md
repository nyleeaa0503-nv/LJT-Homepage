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
* **Ph.D. in Computer Science** (2024–Present)  
  *Hong Kong University of Science and Technology (HKUST)*  
  Advisor: Prof. Junxian He  
  Research: Natural language processing, machine learning, LLM truthfulness and reasoning

* **B.Eng.** (2020–2024)  
  *Shanghai Jiao Tong University (SJTU)*  
  Graduated with honors; recipient of Zhiyuan Honor Scholarship

Work experience
======
* **Research Intern** (February 2025 – Present)  
  *MINIMAX*  
  Working on large language model reasoning and verifiable data synthesis.

* **Research Intern** (June 2024 – September 2024)  
  *Tencent WXG*  
  Advised by Zifei Shan; focused on vision‑language models for chart understanding.

* **Research Intern** (June 2023 – December 2023)  
  *Shanghai AI Lab*  
  Advised by Prof. Yu Cheng; worked on truthfulness hyperplanes in large language models.

Skills
======
* **Natural Language Processing**  
  LLM reasoning, hallucination mitigation, truthfulness, interpretability, evaluation

* **Machine Learning**  
  Deep learning, reinforcement learning, model fine‑tuning, parameter‑efficient methods

* **Programming & Tools**  
  Python, PyTorch, Git, LaTeX, Jupyter, Linux

* **Languages**  
  Chinese (native), English (fluent)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Reviewer for conferences: EMNLP 2024, ICML 2024, NeurIPS 2024
* Open‑source contributor to several NLP projects