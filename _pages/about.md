---
permalink: /
title: "About"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year PhD candidate at the [HKUST NLP Group](https://hkust-nlp.github.io/), advised by [Professor Junxian He](https://jxhe.github.io/). My research focuses on natural language processing and machine learning, with particular interests in LLM reasoning and reinforcement learning, hallucination in vision-language models, and LLM truthfulness and interpretability.

Before starting my PhD, I received my B.Eng. from Shanghai Jiao Tong University (SJTU) in June 2024. During my undergraduate studies, I was advised by Professor Junxian He.

## Research Interests

- **Natural Language Processing**
- **Machine Learning**
- **LLM Reasoning and Reinforcement Learning**
- **Hallucination in Vision-Language Models (VLM)**
- **LLM Truthfulness and Interpretability**

## Education

- **Ph.D. in Computer Science** (2024 - Present)
  - Hong Kong University of Science and Technology (HKUST)
  - Advisor: Professor Junxian He

- **B.Eng.** (2020 - 2024)
  - Shanghai Jiao Tong University (SJTU)
  - Graduated June 2024

## Research Experience

- **Research Intern** (February 2025 - Present)
  - MINIMAX

- **Research Intern** (June 2024 - September 2024)
  - Tencent WXG
  - Advisor: Zifei Shan

- **Research Intern** (June 2023 - December 2023)
  - Shanghai AI Lab
  - Advisor: Prof. Yu Cheng

## Publications

{% include base_path %}

{% if site.publication_category %}
  {% for category in site.publication_category  %}
    {% assign title_shown = false %}
    {% for post in site.publications reversed %}
      {% if post.category != category[0] %}
        {% continue %}
      {% endif %}
      {% unless title_shown %}
        &lt;h2&gt;{{ category[1].title }}&lt;/h2&gt;&lt;hr /&gt;
        {% assign title_shown = true %}
      {% endunless %}
      {% include archive-single.html %}
    {% endfor %}
  {% endfor %}
{% else %}
  {% for post in site.publications reversed %}
    {% include archive-single.html %}
  {% endfor %}
{% endif %}

Please see the [Publications](https://agriplifiediigoa.github.io/LJT-Homepage/publications/) page for a complete list of my publications.

## Contact

- **Email:** [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- **GitHub:** [Vicent0205](https://github.com/Vicent0205)
- **Google Scholar:** [Profile](https://scholar.google.com/citations?hl=en&amp;user=tbK9jl4AAAAJ&amp;view_op=list_works&amp;sortby=pubdate)
- **X (Twitter):** [@junteng88716710](https://x.com/junteng88716710)
