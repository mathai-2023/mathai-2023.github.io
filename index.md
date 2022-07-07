---
layout: page
title: MATH-AI
subtitle: "Toward Human-Level Mathematical Reasoning"
# venue: "NeurIPS Workshop 2021, December 13, 2021"
use-site-title: true
---
<div class="venue" style="font-size: 27px; display: block; font-family: 'Open Sans', 'Helvetica Neue', Helvetica, Arial, sans-serif; font-weight: 300; color: #404040; text-align: center;">
  (NeurIPS 2022 Workshop: <a href="https://neurips.cc/Conferences/2022" target="_blank">Website</a>)
</div>



<div class="sharethis-inline-share-buttons"></div>
<meta name="thumbnail" content="./img/neurips-logo-new.jpg" />

# Previous MATH-AI Workshops

<div class="container" style="margin-bottom: 10px;"></div>

- 1st MATH-AI Workshop at ICLR'21: [The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- MATHAI4ED Workshop at NeurIPS'21: [Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)

<div class="container" style="margin-bottom: 10px;"></div>

# Overview

Mathematical reasoning is a core ability of human intelligence and plays an important role in the development of general machine intelligence. The machine learning community has contributed significantly to mathematical reasoning research in the last decades, and recently, there has been a surge of interest in this domain. For example, large neural models have led to rapid progress in areas ranging from  word problems to formal theorem proving. However, there is a large performance gap between models and top mathematicians. To this end, the MATH-AI workshop will center around the question: 

*“How can machines achieve human-level mathematical reasoning?”*

Specifically, the goal of this workshop is to find out “when machines can surpass human experts in different mathematical domains?”. To investigate this question, we are interested in bringing together a group of scholars from various backgrounds, institutions, and disciplines to discuss areas related to the following:
- **Humans vs. machines**: How does human-level mathematical reasoning differ from today's methods?
- **Measurement**: How should we measure and benchmark progress moving forward?
- **Key technical areas**: What machine learning advances are needed to close the gap with humans?
- **Beyond human-level**: Is human-level reasoning the right goal for all aspects of mathematics?
- **Augmentations**: How can we develop methods that can augment humans in performing mathematical reasoning tasks (e.g. teaching, formulating conjectures,  identifying interesting theorems to prove)?

The intended outcome is to identify missing elements and meaningful directions for future research related to mathematical reasoning. To this end, we welcome papers on areas related, but not limited, to:

- **Problem solving**: informal  and symbolic problem solving tasks and associated methods (e.g.  word and geometry problems, IQ tests, symbolic regression).
- **Theorem proving**: machine learning methods for automated and interactive theorem proving and related problems (e.g. conjecturing, autoformalization).
- **Reasoning in related areas**: program synthesis and software verification, common-sense andnatural language reasoning, retrosynthesis analysis, cognitive and neurosymbolic reasoning mechanisms.

In addition to the problem areas above, we are interested in research related to the following themes:
- **Algorithms**: Can better algorithms (e.g. learning, planning) close the gap with human-level abilities?
- **Analysis**: What are the drawbacks or limitations of current models and evaluation methods with respect to mathematical reasoning (e.g. robustness, generalization)? 
- **Flexibility**: How do we build mathematical reasoning systems that are generic and flexible?
- **Reliability**: How can we ensure that models generate reliable and trustworthy results?
- **Transfer**: Can we leverage common structure between tasks to improve general mathematical ability?


<!-- | ------------- |:-------------:|
| **Submission** | October 09, 2020 (midnight Pacific Time) |
| **Notification** | October 30, 2020 |
| **Submission link**| [https://cmt3.research.microsoft.com/KR2ML2020](https://cmt3.research.microsoft.com/KR2ML2020) -->

<!--* Thank you Amazon for sponsoring a best paper award!
* The 3 best papers will be presented in talks at the workshop! 
* <a href="schedule">The schedule is online now!</a> 
* <a href="papers">List of accepted papers available!</a> -->
<!--* **NEW** Updates to existing submissions possible until October 12 (11:59pm Pacific Time) <br>New submissions close on October 09 (11:59pm Pacific Time)-->


<hr>

# Speakers & Panelists
<div class="container" style="margin-top: 20px;margin-bottom: 0px;">
  <div class="row">
    {% for p in site.data.speakers %}
    {% if forloop.index<=4 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>4 and forloop.index<=10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.speakers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>10%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
<a href="speakers">More Info</a>
</div>

<hr>

# Organizers

<!-- prettier-ignore -->
<div class="container" style="margin-top: 25px;margin-bottom: 40px;">
  <div class="row">
    {% for p in site.data.organizers %}
    {% if forloop.index<=3 %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
  <div class="row">
    {% for p in site.data.organizers %}
    {% capture id %}{{ p[0] }}{% endcapture %}
    {% if forloop.index>3 and forloop.index<=6%}
    {% include profile.html p=p %}
    {% endif %}
    {% endfor %}
  </div>
</div>
<hr>

# Program Committee
<div class="container">
  <ul class="list-group list-group-flush">
    {% for p in site.data.pc.people %}
      <li class="list-group-item col-xs-6 col-sm-4 col-md-3">{{ p }}</li>
    {% endfor %}
  </ul>
</div>
<hr>

# Related Venues

<div class="container" style="margin-bottom: 10px;"></div>
- [NeurIPS'21 workshop on MATHAI4ED - Math AI for Education: Bridging the Gap Between Research and Smart Education](https://mathai4ed.github.io/)
- [ICLR'21 workshop on MATH-AI - The Role of Mathematical Reasoning in General Artificial Intelligence](https://mathai-iclr.github.io/)
- [NeurIPS'20 Workshop on KR2ML - Knowledge Representation & Reasoning Meets Machine Learning](https://kr2ml.github.io/2020)
- [NeurIPS'20 workshop on Advances and Opportunities: Machine Learning for Education](https://www.ml4ed.org/)
- [ICML'20 workshop on Bridge  Between Perception and Reasoning: Graph Neural Networks & Beyond](https://logicalreasoninggnn.github.io)

<div class="container" style="margin-bottom: 10px;"></div>

<hr>

Contact: <mathai2022@gmail.com>.
