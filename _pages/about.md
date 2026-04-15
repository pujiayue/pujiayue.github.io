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


<!-- 
My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>).
-->

# 👋 About Me
Hi! I am Jiayue Pu(浦嘉越), a junior majoring in Computer Science at [University of Chinese Academy of Sciences, China](https://www.ucas.ac.cn/), fortunately supervised by [Prof. Xueqi Cheng](https://scholar.google.com/citations?user=hY8aLqAAAAAJ&hl=en) and [Prof. Fei Sun](http://ofey.me/). My current research interest lies in Trustworthy AI, especially in Large Language Models (Agents) Unlearning and Hallucination.

During my freshman year at university, driven by a strong passion for information security, I actively participated in Capture the Flag (CTF) competitions and achieved some notable results. As I progressed into my sophomore year, I joined the Key Laboratory of AI Safety at the Institute of Computing Technology, Chinese Academy of Sciences, where I researched LLM safety under the guidance of [Prof. Xueqi Cheng](https://scholar.google.com/citations?user=hY8aLqAAAAAJ&hl=en) and [Fei Sun](http://ofey.me/), with a primary focus on LLM unlearning. Currently, I am a visiting student in the University of California, Berkeley, and conducting research on hallucinations in LLM agents under the guidance of [Dr. Yiyou Sun](https://sunyiyou.github.io/), a postdoctoral researcher in [Prof. Dawn Song](https://dawnsong.io/)'s lab.

# 📖 Educations
- *2022.09 - Present*, B.S. in Computer Science, School of Computer Science and Technology, University of Chinese Academy of Sciences.
- *2025.01 - 2025.05*, Visiting Student in EECS, University of California, Berkeley.
  
# 📝 Publications 

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2026</div><img src='images/homesafe-bench.png' alt="homesafe-bench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[HomeSafe-Bench: Evaluating Vision-Language Models on Unsafe Action Detection for Embodied Agents in Household Scenarios](https://arxiv.org/abs/2603.11975)

**Jiayue Pu**, Zhongxiang Sun, Zilu Zhang, Xiao Zhang, Jun Xu

[**arXiv**](https://arxiv.org/abs/2603.11975) | [**Project Page**](https://pujiayue.github.io/homesafe-bench.github.io/) | [**Code**](https://github.com/pujiayue/HomeSafe-Bench) | [**Dataset**](https://drive.google.com/drive/folders/1mMTKtmGmu-dBdylRZUoPt3QRKmDe_gk4) | [**Leaderboard**](https://huggingface.co/spaces/pujiayue/HomeSafe-Bench-Leaderboard)
- We introduce HomeSafe-Bench, a challenging benchmark designed to evaluate Vision-Language Models (VLMs) on unsafe action detection in household scenarios, featuring 438 diverse cases across six functional areas. We also propose HD-Guard, a hierarchical streaming architecture for real-time safety monitoring.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/miragebench.png' alt="mirage-bench" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[MIRAGE-Bench: LLM Agent is Hallucinating and Where to Find Them](https://arxiv.org/abs/2507.21017)

Weichen Zhang, Yiyou Sun, Pohao Huang, **Jiayue Pu**, Heyue Lin, Dawn Song

[**arXiv**](https://arxiv.org/abs/2507.21017) | [**Code & Data**](https://github.com/sunblaze-ucb/mirage-bench)
- We present MIRAGE-Bench, the first unified benchmark for eliciting and evaluating hallucinations in interactive LLM-agent scenarios. It introduces a three-part taxonomy and adopts a fine-grained-level LLM-as-a-Judge paradigm with tailored risk-aware prompts.
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/unlearning.png' alt="unlearning-survey" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[A Survey on Unlearning in Large Language Models](https://arxiv.org/abs/2510.25117)

Ruichen Qiu, Jiajun Tan, **Jiayue Pu**, Honglin Wang, Xiao-Shan Gao, Fei Sun

[**arXiv**](https://arxiv.org/abs/2510.25117)
- This survey provides a systematic review of over 180 papers on LLM unlearning published since 2021. It introduces a novel taxonomy categorizing unlearning methods and offers a multidimensional analysis of evaluation paradigms, datasets, and metrics.
</div>
</div>

# 💻 Internships
- *2023.09 - Present*, Institute of Computing Technology, Chinese Academy of Sciences，Research Intern, advised by [Prof. Fei Sun](http://ofey.me/).
- *2024.09 - 2025.05*, Berkeley AI Safety Initiative, group members.
- *2024.09 - 2025.05*, University of California, Berkeley, Research Collaborator, advised by [Postdoc. Yiyou Sun](https://sunyiyou.github.io/).
- *2025.08 - Present*, Gaoling School of Artificial Intelligence, Renmin University of China, co-advised by [Prof. XiaoZhang](https://gsai.ruc.edu.cn/gsaixiaozhang) and [Prof. Jun Xu](https://gsai.ruc.edu.cn/~junxu).

# 🥇 Honors and Awards
- **National Scholarship**, Ministry of Education of P.R.China
  - Awarded in *November 2024*
- **Outstanding Triple-A Student**,  University of Chinese Academy of Sciences
  - Awarded in *June 2024*
- **Triple-A Student**, University of Chinese Academy of Sciences
  - Awarded in *June 2023* and *June 2024*
- **Outstanding Communist Youth League Member**, University of Chinese Academy of Sciences
  - Awarded in *June 2023* and *June 2024*
- **First Class Academic Scholarship**, University of Chinese Academy of Sciences
  - Awarded in *October 2023*


# 🤝 Meetings
- ACL(The Association for Computational Linguistics) 2024, Bangkok, Thailand
- EMNLP (Empirical Methods in Natural Language Processing) 2025, Su Zhou, China
  
<!--
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)
-->

# 👩 Public Affairs
- Peer Mentor of Class 2412
- Principal Cellist of the UCAS Philharmonic Orchestra
- President of the Undergraduate Choir, University of Chinese Academy of Sciences
- Officer of the Student Societies Center, Undergraduate Student Union, University of Chinese Academy of Sciences
- Vice Class Representative, Class of 2206, Computer Science and Technology, University of Chinese Academy of Sciences
