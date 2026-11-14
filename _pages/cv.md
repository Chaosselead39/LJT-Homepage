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
* **Ph.D. in Computer Science**, Hong Kong University of Science and Technology, 2024–Present
  * HKUST NLP Group; first-year PhD candidate
  * Supervisor: Prof. Junxian He
* **B.Eng.**, Shanghai Jiao Tong University, 2020–2024; graduated in June 2024; previously advised by Prof. Junxian He
* Zhiyuan Honor Scholarship, Shanghai Jiao Tong University

Research Experience
======
* **Research Intern**, MINIMAX, February 2025–Present
* **Research Intern**, Tencent WXG, June 2024–September 2024; advisor: Zifei Shan
* **Research Intern**, Shanghai AI Lab, June 2023–December 2023; advisor: Prof. Yu Cheng

Research Skills and Interests
======
* Natural language processing and machine learning
* LLM reasoning and reinforcement learning
* Hallucination in vision-language models (VLMs)
* LLM truthfulness and interpretability

Publications
======
  {% assign publications_by_date = site.publications | sort: "date" | reverse %}
  <ul>{% for post in publications_by_date %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Contact
======
* Email: [jliugi@connect.ust.hk](mailto:jliugi@connect.ust.hk)
* GitHub: [Vicent0205](https://github.com/Vicent0205)
* Google Scholar: [Google Scholar profile](https://scholar.google.com/citations?hl=en&user=tbK9jl4AAAAJ&view_op=list_works&sortby=pubdate)
* X (Twitter): [@junteng88716710](https://twitter.com/junteng88716710)
