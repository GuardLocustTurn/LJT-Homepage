---
layout: archive
title: "Curriculum Vitae"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

## Education

- **Ph.D. in Computer Science**, The Hong Kong University of Science and Technology, 2024–Present.
  - HKUST NLP Group; supervisor: Professor Junxian He.
- **B.Eng.**, Shanghai Jiao Tong University, 2020–2024.
  - Graduated in June 2024.
  - Previously advised during undergraduate studies by Professor Junxian He.

## Research Experience

- **Research Intern**, MINIMAX, February 2025–Present.
- **Research Intern**, Tencent WXG, June 2024–September 2024; advisor: Zifei Shan.
- **Research Intern**, Shanghai AI Lab, June 2023–December 2023; advisor: Prof. Yu Cheng.
- **PhD Researcher**, HKUST NLP Group, 2024–Present; supervisor: Professor Junxian He.

## Research Skills and Interests

- Natural language processing and machine learning.
- LLM reasoning and reinforcement learning.
- Hallucination in vision-language models (VLM).
- LLM truthfulness and interpretability.

## Honors

- Zhiyuan Honor Scholarship, Shanghai Jiao Tong University.

## Publications

{% assign cv_publications = site.publications | sort: "year" | reverse %}
{% for post in cv_publications %}
- **{{ post.title }}**. {{ post.authors }} *{{ post.venue }} ({{ post.year }})*.{% if post.role %} {{ post.role }}.{% endif %}{% if post.code_repository %} Code repository: `{{ post.code_repository }}`.{% endif %}
{% endfor %}

The formatted publication entries are available on the [Publications page]({{ '/publications/' | relative_url }}).

## Contact

- Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
- GitHub: [https://github.com/Vicent0205](https://github.com/Vicent0205)
- Google Scholar: [Profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
- X (Twitter): [@junteng88716710](https://x.com/junteng88716710)
