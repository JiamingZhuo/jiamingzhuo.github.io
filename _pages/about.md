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

Hello! I am Jiaming Zhuo (禚佳明), a Ph.D. Candidate at School of Artificial Intelligence, Hebei University of Technology, supervised by Prof. [Liang Yang (杨亮)](https://yangliang.github.io/). 

<!-- My research interest includes (audio-only or audio-visual) speech processing: enhancement, extraction and seperation; speaker processing: recognition, diarization, active speaker detection and anti-spoofing. I also work in self-supervised learning. I have published more than 20 papers at the top international AI conferences and journals such as TASLP, TMM, ACM MM, ICASSP, INTERSPEECH. <a href='https://scholar.google.com/citations?user=sdXITx8AAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2FTaoRuijie%2Ftaoruijie.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> -->

# 📜 Research Area

| Research Area | Topic |
| -------- | -------- |
| Graph Learning  | Graph Self-supervised Learning, Graph Transformer |
| Bioinformatics | Spatial Transcriptomics Analysis |

# 🏫 Education

- *2022.09 - *, Ph.D. in Control Science and Engineering, Hebei University of Technology, Tianjin, China. (Integrated Master-Ph.D. Program)
- *2019.09 - *, M.Sc. in Computer Science and Technology, Hebei University of Technology, Tianjin, China. 
- *2017.09 - 2019.06*, B.Eng. in Computer Science and Technology, Linyi University, Shandong, China.

<!-- # Working Experience
- *2024.12 - Now*, Audio AI Enginner, Zoom, Singapore.
- *2023.08 - 2024.11*, Research Fellow, National University of Singapore (NUS), Singapore. -->


# 📝 Publication

- [DUALFormer: Dual Graph Transformer](https://openreview.net/pdf?id=4v4RcAODj9). **Jiaming Zhuo**, Yuwei Liu, Yintong Lu, Ziyi Ma, Kun Fu, Chuan Wang, Yuanfang Guo, Zhen Wang, Xiaochun Cao, Liang Yang, **ICLR**, 2025.
- [Unified Graph Augmentations for Generalized Contrastive Learning on Graphs](https://proceedings.neurips.cc/paper_files/paper/2024/file/41efc12982eca6f8bb5e48dc3a84b843-Paper-Conference.pdf). **Jiaming Zhuo**, Yintong Lu, Hui Ning, Kun Fu, Bingxin Niu, Dongxiao He, Chuan Wang, Yuanfang Guo, Zhen Wang, Xiaochun Cao, Liang Yang, **NeurIPS**, 2024.
- [Improving Graph Contrastive Learning via Adaptive Positive Sampling](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10657133). **Jiaming Zhuo**, Feiyang Qin, Can Cui, Kun Fu, Bingxin Niu, Mengzhu Wang, Yuanfang Guo, Chuan Wang, Zhen Wang, Xiaochun Cao, Liang Yang. **CVPR**, 2024. 
<!-- - , [![](https://img.shields.io/github/stars/TaoRuijie/MFV-KSD?style=social&label=Code+Stars)](https://github.com/TaoRuijie/MFV-KSD) -->
- [Graph Contrastive Learning Reimagined: Exploring Universality](https://dl.acm.org/doi/10.1145/3589334.3645480). **Jiaming Zhuo**, Can Cui, Kun Fu, Bingxin Niu, Dongxiao He, Chuan Wang, Yuanfang Guo, Zhen Wang, Xiaochun Cao, Liang Yang. **WWW**, 2024.
- [Propagation is All You Need: A New Framework for Representation Learning and Classifier Training on Graphs](https://dl.acm.org/doi/10.1145/3581783.3612196), **Jiaming Zhuo**, Can Cui, Kun Fu, Bingxin Niu, Dongxiao He, Yuanfang Guo, Zhen Wang, Chuan Wang, Xiaochun Cao, Liang Yang, **MM**, <font color="red">Oral</font>, 2023.

---

- [Do We Really Need Message Passing in Brain Network Modeling?](https://jiamingzhuo.github.io/), Liang Yang, Yuwei Liu, **Jiaming Zhuo (Corresponding Author)**, Di Jin, Chuan Wang, Zhen Wang, Xiaochun Cao. **ICML**, <font color="green">Spotlight</font>, 2025. 
- [Universal Graph Self-Contrastive Learning](https://jiamingzhuo.github.io/). Liang Yang, Yukun Cai, Hui Ning, **Jiaming Zhuo (Corresponding Author)**, Di Jin, Ziyi Ma, Yuanfang Guo, Chuan Wang, Zhen Wang, **IJCAI**, 2025.
- [Graph Contrastive Learning with Joint Spectral Augmentation of Attribute and Topology](https://ojs.aaai.org/index.php/AAAI/article/view/35506). Liang Yang, Zhenna Li, **Jiaming Zhuo (Corresponding Author)**, Jing Liu, Ziyi Ma, Chuan Wang, Zhen Wang, Xiaochun Cao, **AAAI**, <font color="red">Oral</font>, 2025. 
- [Disentangled Graph Spectral Domain Adaptation](https://jiamingzhuo.github.io/), Liang Yang, Xin Chen, Jiaming Zhuo, Di Jin, Chuan Wang, Xiaochun Cao, Zhen Wang, Yuanfang Guo, **ICML**, 2025.


<!-- # 💻 Open Source Code
- *Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/ECAPATDNN?style=social&label=ECAPA-TDNN)](https://github.com/TaoRuijie/ECAPATDNN)
- *Active Speaker Detection Framework* [![](https://img.shields.io/github/stars/TaoRuijie/TalkNet_ASD?style=social&label=TalkNet-ASD)](https://github.com/TaoRuijie/TalkNet_ASD)
- *Self-supervised Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/Loss-Gated-Learning?style=social&label=LGL)](https://github.com/TaoRuijie/Loss-Gated-Learning)
- *Audio-visual Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/AVCleanse?style=social&label=AVCleanse)](https://github.com/TaoRuijie/AVCleanse)
- *Cross-modal Speaker Recognition Framework* [![](https://img.shields.io/github/stars/TaoRuijie/MFV-KSD?style=social&label=MFV-KSD)](https://github.com/TaoRuijie/MFV-KSD)
- *Ego4d Benchmark* [![](https://img.shields.io/github/stars/facebookresearch/Ego4d?style=social&label=Ego4d)](https://github.com/facebookresearch/Ego4d) -->

# 👔 Internship and Visiting Experience

- *2025.08 - *, Visiting Student, , Institute of High Performance Computing (IHPC), Agency for Science, Technology and Research (ASTAR), Singapore.


# 🎖 Others

**Award**

- Top 10 Academic Stars Award, Hebei University of Technology, 2024.
- Academic Stars Award, School of Artificial Intelligence, Hebei University of Technology, 2024.
- First-class Scholarships for Postgraduate Studies, Hebei University of Technology, 2022-2023, 2023-2024, 2024-2025.
- Notable Reviewers, ICLR, 2025

**Reviewer**

- International Conference on Learning Representations (ICLR), 2025.
- Conference on Neural Information Processing Systems (NeurIPS), 2024-2025.
- International Conference on Machine Learning (ICML), 2024-2025.
- International World Wide Web Conference (WWW), 2025.
- ACM International Conference on Multimedia (MM), 2025.


<!-- **Teaching**

- EE3801 Data Engineering Principles, NUS undergraduate course
- EE5132 Wireless and Sensor Networks, NUS graduate course -->

