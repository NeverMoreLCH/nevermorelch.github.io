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

# 📜 Biography
<span class='anchor' id='about-me'></span>

I am a research in Shanghai AI Lab, collaborating closely with Dr. [Kaipeng Zhang](https://kpzhang93.github.io/) and Dr. [Wenqi Shao](https://wqshao126.github.io/).
I recevied my Ph.D. degree in 2025 from Beijing Institute of Technology (BIT), advised by Prof. [Yuwei Wu](https://wu-yuwei-bit.github.io/) and Prof. [Yunde Jia](https://scholar.google.com/citations?user=Sl6TV7gAAAAJ&hl=zh-CN),
Master degree in 2020 from Northeastern University supervised by Prof. [Shukuan Lin](http://www.cse.neu.edu.cn/2019/0303/c6664a159411/page.htm),
and Bachlor degree in 2017 from Harbin University of Science and Technology.

My research area lies at:
- vision-and-language
- image/video generation
- multimodal large language models
- compositional generalization

<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2020.09 - 2025.03*, <a href="https://www.bit.edu.cn/"><img class="png" src="/images/BIT_logo.png" width="23pt"></a> Ph.D. in CS, Beijing Institute of Technology, Beijing, China
- *2017.09 - 2020.01*, <a href="https://www.neu.edu.cn/"><img class="png" src="/images/NEU_logo.png" width="23pt"></a> Master in CS, Northeastern University, Shenyang, Liaoning, China
- *2013.09 - 2017.06*, <a href="https://www.hrbust.edu.cn/"><img class="png" src="/images/HRBUST_logo.png" width="23pt"></a>  Bachelor in CS, Harbin University of Science and Technology, Harbin, Heilongjiang, China
 
<span class='anchor' id='-arxiv'></span>

# ⚡ Preprint

**ARMOR: Empowering Autoregressive Multimodal Understanding Model with Interleaved Multimodal Generation via Asymmetric Synergy**
- Jianwen Sun, Yukang Feng, `Chuanhao Li`, Fanrui Zhang, Zizhen Li, Jiaxin Ai, Sizhuo Zhou, Pengfei Zhou, Yu Dai, Shenglin Zhang, and Kaipeng Zhang.
- [arXiv 2025] [[paper]](https://arxiv.org/abs/2503.06542) [[code]](https://armor.github.io/)

<span class='anchor' id='-lwzl'></span>

# 📝 Publications

**GATE OpenING: A Comprehensive Benchmark for Judging Open-ended Interleaved Image-Text Generation**
- Pengfei Zhou, Xiaopeng Peng, Jiajun Song, `Chuanhao Li`, Zhaopan Xu, Yue Yang, Ziyao Guo, Hao Zhang, Yuqi Lin, Yefei He, Lirui Zhao, Shuo Liu, Tianhua Li, Yuxuan Xie, Xiaojun Chang, Yu Qiao, Wenqi Shao, and Kaipeng Zhang.
- [CVPR 2025] **[Oral] (Top 3.3%)** [[paper]](https://arxiv.org/abs/2411.18499) [[code]](https://opening-benchmark.github.io/)

**MMIU: Multimodal Multi-image Understanding for Evaluating Large Vision-Language Models**
- Fanqing Meng\*, Jin Wang\*, `Chuanhao Li*`, Quanfeng Lu, Hao Tian, Jiaqi Liao, Xizhou Zhu, Jifeng Dai, Yu Qiao, Ping Luo, Kaipeng Zhang, and Wenqi Shao. (\* equal contribution)
- [ICLR 2025] [[paper]](https://arxiv.org/abs/2408.02718) [[code]](https://mmiu-bench.github.io/)

**Consistency of Compositional Generalization across Multiple Levels**
- `Chuanhao Li`, Zhen Li, Chenchen Jing, Xiaomeng Fan, Wenbo Ye, Yuwei Wu, and Yunde Jia.
- [AAAI 2025] [[paper]](https://arxiv.org/pdf/2412.13636) [[code]](https://github.com/NeverMoreLCH/CCG)

**SearchLVLMs: A Plug-and-Play Framework for Augmenting Large Vision-Language Models by Searching Up-to-Date Internet Knowledge**
- `Chuanhao Li`, Zhen Li, Chenchen Jing, Shuo Liu, Wenqi Shao, Yuwei Wu, Ping Luo, Yu Qiao, and Kaipeng Zhang.
- [NeurIPS 2024] [[paper]](https://nips.cc/virtual/2024/poster/93813) [[code]](https://nevermorelch.github.io/SearchLVLMs.github.io/)

**ConvBench: A Multi-Turn Conversation Evaluation Benchmark with Hierarchical Capability for Large Vision-Language Models**
- Shuo Liu, Kaining Ying, Hao Zhang, Yue Yang, Yuqi Lin, Tianle Zhang, `Chuanhao Li`, Yu Qiao, Ping Luo, Wenqi Shao, and Kaipeng Zhang.
- [NeurIPS 2024] **[Spotlight]** [[paper]](https://arxiv.org/abs/2403.20194) [[code]](https://github.com/shirlyliu64/ConvBench)

**Compositional Substitutivity of Visual Reasoning for Visual Question Answering**
- `Chuanhao Li`, Zhen Li, Chenchen Jing, Yuwei Wu, Mingliang Zhai, and Yunde Jia.
- [ECCV 2024] [[paper]](https://www.ecva.net/papers/eccv_2024/papers_ECCV/papers/06434.pdf) [[code]](https://github.com/NeverMoreLCH/CG-SPS)

**In-Context Compositional Generalization for Large Vision-Language Models**
- `Chuanhao Li`, Chenchen Jing, Zhen Li, Mingliang Zhai, Yuwei Wu, and Yunde Jia.
- [EMNLP 2024] [Main Conference] [[paper]](https://aclanthology.org/2024.emnlp-main.996.pdf)

**Adversarial Sample Synthesis for Visual Question Answering**
- `Chuanhao Li`, Chenchen Jing, Zhen Li, Yuwei Wu, and Yunde Jia.
- [TOMM 2024] [[paper]](https://dl.acm.org/doi/10.1145/3688848)

**Exploring the Effect of Primitives for Compositional Generalization in Vision-and-Language**
- `Chuanhao Li`, Zhen Li, Chenchen Jing, Yuwei Wu, and Yunde Jia.
- [CVPR 2023] [[paper]](http://openaccess.thecvf.com/content/CVPR2023/papers/Li_Exploring_the_Effect_of_Primitives_for_Compositional_Generalization_in_Vision-and-Language_CVPR_2023_paper.pdf) [[code]](https://github.com/NeverMoreLCH/SSL2CG)

**Learning the Dynamics of Visual Relational Reasoning via Reinforced Path Routing**
- Chenchen Jing, Yunde Jia, Yuwei Wu, `Chuanhao Li`, and Qi Wu.
- [AAAI 2022] [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/19997/19756)
    
<span class='anchor' id='-ryjx'></span>

# 🏅 Selected Awards
- *2023.01*, the second prize in the multi-modal technology innovation competition of the first “Xingzhi Cup” National Artificial Intelligence Innovation Application Competition
- *2016.05*, the first prize in the CCPC Heilongjiang Collegiate Programming Contest
- *2015.05*, the first prize in the CCPC Heilongjiang Collegiate Programming Contest
- *2014.07*, the silver medal in the ACM-ICPC Collegiate Programming Contest Shanghai Invitational

<span class='anchor' id='-xshy'></span>

# 🏛️ Academic Activities
- Conference Reviewer of MM2025, ICCV 2025, ICML 2025, IJCAI 2025, CVPR 2024, NeurIPS 2024, MM 2024, etc.
- Journal Reviewer of T-MM.
- Invited Speaker in [The 3rd SMBU-BIT Machine Intelligence Graduate Student Forum](https://www.smbu.edu.cn/zskxwhj/info/1097/3708.htm).

<span class='anchor' id='-gzsx'></span>

# 💻 Work Experience
- *2025.04 - Present*, Researcher, Shanghai AI Lab, Shanghai, China
- *2024.01 - 2025.04*, Intern, Shanghai AI Lab, Shanghai, China
- *2019.07 - 2019.10*, Intern, UISEE, Beijing, China
