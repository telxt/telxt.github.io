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

# 👋 About Me

Hi! I am a Ph.D. student in [Tsinghua University](https://www.tsinghua.edu.cn/), advised by [Prof. Bowen Zhou](https://c3i.ee.tsinghua.edu.cn/en/author/bowen-zhou/). I received my bachelor’s degree with honors from [Tsinghua University](https://www.tsinghua.edu.cn/) in June 2024. My research interests include LLM post-training (especially reinforcement learning), agents, and model architecture design.

<span class='anchor' id='news'></span>

# 🌟 News

- *2026.05*: &nbsp;🔥 [ZEDA](https://arxiv.org/abs/2605.18643) released at arXiv [[GitHub]](https://github.com/TsinghuaC3I/ZEDA)
- *2025.09*: &nbsp;🔥 [UPGE / HPT](https://arxiv.org/abs/2509.04419) released at arXiv [[GitHub]](https://github.com/TsinghuaC3I/Unify-Post-Training)
- *2025.03*: &nbsp;🔥 [SSM Survey](https://arxiv.org/abs/2503.11224) released at arXiv
- *2024.11*: &nbsp;🎉 [Low-dimensional Projected Attention](https://arxiv.org/abs/2411.02063) accepted by EMNLP 2024 [[GitHub]](https://github.com/TsinghuaC3I/LPA)
- *2023.12*: &nbsp;🎉 [Sparse LoRA](https://arxiv.org/abs/2311.11696) accepted by EMNLP 2023 [[GitHub]](https://github.com/TsinghuaC3I/SoRA)
- *2023.07*: &nbsp;🎉 [Parameter-efficient Weight Ensembling Facilitates Task-level Knowledge Transfer](https://aclanthology.org/2023.acl-short.24/) accepted by ACL 2023 [[GitHub]](https://github.com/telxt/Delta_search)

<span class='anchor' id='publications'></span>

# 📝 Highlight Publications

(* denotes equal contribution)

- [Post-Trained MoE Can Skip Half Experts via Self-Distillation](https://arxiv.org/abs/2605.18643)<br>
  **Xingtai Lv**\*, Li Sheng\*, Kaiyan Zhang\*, Yichen You, Siyan Gao, Xueheng Luo, Yuxin Zuo, Yuchen Fan, Junlin Yang, Ganqu Cui, Bingning Wang, Fan Yang, Youbang Sun, Ning Ding, Bowen Zhou<br>
  *Preprint* [[GitHub]](https://github.com/TsinghuaC3I/ZEDA)
- [Towards a Unified View of Large Language Model Post-Training](https://arxiv.org/abs/2509.04419)<br>
  **Xingtai Lv**\*, Yuxin Zuo\*, Youbang Sun, Hongyi Liu, Yuntian Wei, Zhekai Chen, Xuekai Zhu, Kaiyan Zhang, Bingning Wang, Ning Ding, Bowen Zhou<br>
  *Preprint* [[GitHub]](https://github.com/TsinghuaC3I/Unify-Post-Training)
- [A Survey of Reinforcement Learning for Large Reasoning Models](https://arxiv.org/abs/2509.08827)<br>
  Kaiyan Zhang\*, Yuxin Zuo\*, Bingxiang He\*, Youbang Sun\*, Runze Liu\*, Che Jiang\*, Yuchen Fan\*, Kai Tian\*, Guoli Jia\*, Pengfei Li\*, Yu Fu\*, **Xingtai Lv**\*, Yuchen Zhang\*, Sihang Zeng\*, Shang Qu\*, Haozhan Li\*, Shijie Wang\*, Yuru Wang\*, Xinwei Long, Fangfu Liu, Xiang Xu, Jiaze Ma, Xuekai Zhu, Ermo Hua, Yihao Liu, Zonglin Li, Huayu Chen, Xiaoye Qu, Yafu Li, Weize Chen, Zhenzhao Yuan, Junqi Gao, Dong Li, Zhiyuan Ma, Ganqu Cui, Zhiyuan Liu, Biqing Qi, Ning Ding, Bowen Zhou<br>
  *Preprint* [[GitHub]](https://github.com/TsinghuaC3I/Awesome-RL-for-LRMs)
- [Technologies on Effectiveness and Efficiency: A Survey of State Spaces Models](https://arxiv.org/abs/2503.11224)<br>
  **Xingtai Lv**\*, Youbang Sun\*, Kaiyan Zhang\*, Shang Qu, Xuekai Zhu, Yuchen Fan, Yi Wu, Ermo Hua, Xinwei Long, Ning Ding, Bowen Zhou<br>
  *Preprint*
- [Process Reinforcement through Implicit Rewards](https://arxiv.org/abs/2502.01456)<br>
  Ganqu Cui\*, Lifan Yuan\*, Zefan Wang\*, Hanbin Wang\*, Yuchen Zhang, Jiacheng Chen, Wendi Li\*, Bingxiang He\*, Yuchen Fan\*, Tianyu Yu\*, Qixin Xu\*, Weize Chen, Jiarui Yuan, Huayu Chen, Kaiyan Zhang, **Xingtai Lv**, Shuo Wang, Yuan Yao, Xu Han, Hao Peng, Yu Cheng, Zhiyuan Liu, Maosong Sun, Bowen Zhou, Ning Ding<br>
  *Preprint* [[GitHub]](https://github.com/PRIME-RL/PRIME)
- [Scalable Efficient Training of Large Language Models with Low-dimensional Projected Attention](https://arxiv.org/abs/2411.02063)<br>
  **Xingtai Lv**, Ning Ding, Kaiyan Zhang, Ermo Hua, Ganqu Cui, Bowen Zhou<br>
  *EMNLP 2024* [[GitHub]](https://github.com/TsinghuaC3I/LPA)
- [Sparse Low-rank Adaptation of Pre-trained Language Models](https://arxiv.org/abs/2311.11696)<br>
  Ning Ding\*, **Xingtai Lv**\*, Qiaosen Wang, Yulin Chen, Bowen Zhou, Zhiyuan Liu, Maosong Sun<br>
  *EMNLP 2023* [[GitHub]](https://github.com/TsinghuaC3I/SoRA)
- [Parameter-efficient Weight Ensembling Facilitates Task-level Knowledge Transfer](https://aclanthology.org/2023.acl-short.24/)<br>
  **Xingtai Lv**\*, Ning Ding\*, Yujia Qin, Zhiyuan Liu, Maosong Sun<br>
  *ACL 2023* [[GitHub]](https://github.com/telxt/Delta_search)

<span class='anchor' id='educations'></span>

# 📖 Educations

- *2024.09 - now*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  Ph.D. in Electrical Engineering ([THUC3I](https://c3i.ee.tsinghua.edu.cn/en/))
- *2020.09 - 2024.06*, [Tsinghua University](https://www.tsinghua.edu.cn/)
  B.S. in Electrical Engineering, ranked 1st/251

<span class='anchor' id='honors-and-awards'></span>

# 🎖 Honors and Awards

* Outstanding Graduate Award, Tsinghua University. *2024.06*
* Outstanding Graduate Award, Beijing Municipal Education Commission. *2024.06*
* Outstanding Paper Award for Diploma Project, Tsinghua University. *2024.06*
* National Scholarship, Ministry of Education of the People's Republic of China. *2023.12*
* Comprehensive Merit Scholarship, Tsinghua University. *2023.12*
* Samsung Scholarship, Samsung Electronics China. *2023.06*
* Second Prize in Freshmen Scholarship, Tsinghua University. *2020.09*

<span class='anchor' id='invited-talks'></span>

# 💬 Invited Talks

- 2025 QingKeAI Carnival - Reinforcement Learning Track. [QingKeAI](https://qingkeai.online/archives/2025-AI-Meetup). *2025.12*
- Towards a Unified View of Large Language Model Post-Training. [QingKeAI](https://qingkeai.online/archives/nZxilbl5). *2025.10*

<span class='anchor' id='services'></span>

# 🛠️ Services

- **Conference Reviewer**: NeurIPS (2026), ICLR (2025 - 2026), ICML (2026), ACL ARR (2023 - 2025)
