---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

Hi, I'm a second year CS PhD student at Cornell Tech working with Vitaly Shmatikov. Currently I'm a Research Intern at <img style="width: 2%;" src="/assets/qwen.png" alt="Qwen Logo"> [Qwen Team](https://github.com/QwenLM) in Shanghai.  My research interest is AI Safety and LLM Control & Intervention. Previously I have also worked on Zero-Knowledge Proofs.

# 📝 Publications 

- ``NSDI 2024`` [Zombie: Middleboxes that Don’t Snoop](https://eprint.iacr.org/2023/1022.pdf), **Collin Zhang**, Zachary DeStefano, Arasu Arun, Joseph Bonneau, Paul Grubbs, Michael Walfish
- ``EMNLP 2024`` [Extracting Prompts by Inverting LLM Outputs](https://arxiv.org/pdf/2405.15012), **Collin Zhang**, John X. Morris, Vitaly Shmatikov

# 📝 Preprints
- [Adversarial Decoding: Generating Readable Documents for Adversarial Objectives](https://arxiv.org/abs/2410.02163), **Collin Zhang**, Tingwei Zhang, Vitaly Shmatikov
- [Soft Prompts Go Hard: Steering Visual Language Models with Hidden Meta-Instructions](https://arxiv.org/pdf/2407.08970), Tingwei Zhang, **Collin Zhang**, John X Morris, Eugene Bagdasaryan, Vitaly Shmatikov
- [Universal Zero-shot Embedding Inversion](https://arxiv.org/abs/2504.00147), **Collin Zhang**, John X. Morris, Vitaly Shmatikov
- [Harnessing the Universal Geometry of Embeddings](https://arxiv.org/abs/2505.12540), Rishi Jha, **Collin Zhang**, Vitaly Shmatikov, John X Morris

<!-- # 🎖 Honors and Awards
- *2021.10* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.09* Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->

# 📖 Educations
- *2023.08 - (now)*, Cornell University, PhD, Computer Science 
- *2019.09 - 2023.05*, New York University Stern School of Business, BS, Computer Science & Econometrics
- *2016.09 - 2019.06*, Nanjing Foreign Language School

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

# 👻 Projects
- [FastDraw](https://github.com/collinzrj/FastDraw) A Fast and Complete Swift Drawing(Handwriting) Library for iOS
- [adversarial_decoding](https://github.com/collinzrj/adversarial_decoding) Generating Readable Documents for Multiple Adversarial Objectives 
- [output2prompt](https://github.com/collinzrj/output2prompt) Inverting Outputs to Prompts

# 🎤 Talks
- Presented **Zombie: Middleboxes that Don’t Snoop** ([Slide](/pdfs/zombie.pdf)) at [Cornell Systems Lunch](https://www.cs.cornell.edu/courses/cs7490/2023fa/) on Sep 22 2023
