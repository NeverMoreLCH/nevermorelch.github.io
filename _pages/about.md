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

# 📜 Biography
I am a research in Shanghai AI Lab, collaborating closely with Dr. [Kaipeng Zhang](https://kpzhang93.github.io/) and Dr. [Wenqi Shao](https://wqshao126.github.io/).
I recevied my Ph.D. degree in 2025 from Beijing Institute of Technology (BIT), advised by Prof. [Yuwei Wu](https://wu-yuwei-bit.github.io/) and Prof. [Yunde Jia](https://scholar.google.com/citations?user=Sl6TV7gAAAAJ&hl=zh-CN),
Master degree in 2020 from Northeastern University supervised by Prof. [Shukuan Lin](http://www.cse.neu.edu.cn/2019/0303/c6664a159411/page.htm),
and Bachlor degree in 2017 from Harbin University of Science and Technology.

My research area lies at:
- vision-and-language
- image/video generation
- multimodal large language models
- internet-augmented generation
- compositional generalization

<span class='anchor' id='-xl'></span>

# 🎓 Education
- *2020.09 - 2025.03*, <a href="https://www.bit.edu.cn/"><img class="png" src="/images/BIT_logo.png" width="23pt"></a> Ph.D. in CS, Beijing Institute of Technology, Beijing, China
- *2017.09 - 2020.01*, <a href="https://www.neu.edu.cn/"><img class="png" src="/images/NEU_logo.png" width="23pt"></a> Master in CS, Northeastern University, Shenyang, Liaoning, China
- *2013.09 - 2017.06*, <a href="https://www.hrbust.edu.cn/"><img class="png" src="/images/HRBUST_logo.png" width="23pt"></a>  Bachelor in CS, Harbin University of Science and Technology, Harbin, Heilongjiang, China
 
<span class='anchor' id='-arxiv'></span>

# ⚡ Preprint
<p style="color:red;"><strong>* indicates equal contribution</strong></p><p style="color:blue;"><strong> + indicates corresponding author</strong></p>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-mao.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **YUME: An Interactive World Generation Model**
  - Xiaofeng Mao, Shaoheng Lin, Zhen Li, `Chuanhao Li`, Wenshuo Peng, Tong He, Jiangmiao Pang, Mingmin Chi<span style="color:blue;">+</span>, Yu Qiao, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2507.17744) [[homepage]](https://stdstu12.github.io/YUME-Project/) [[code]](https://github.com/stdstu12/YUME)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-lizhen.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Sekai: A Video Dataset towards World Exploration**
  - Zhen Li<span style="color:red;">*</span>, `Chuanhao Li`<span style="color:red;">*</span><span style="color:blue;">+</span>, ..., Yuwei Wu<span style="color:blue;">+</span>, Tong He, Jiangmiao Pang, Yu Qiao, Yunde Jia, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2506.15675) [[homepage]](https://lixsp11.github.io/sekai-project/) [[dataset]](https://huggingface.co/datasets/Lixsp11/Sekai-Project) [[code]](https://github.com/Lixsp11/sekai-codebase)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **IA-T2I: Internet-Augmented Text-to-Image Generation**
  - `Chuanhao Li`<span style="color:red;">*</span>, Jianwen Sun<span style="color:red;">*</span>, Yukang Feng<span style="color:red;">*</span>, Mingliang Zhai, Yifan Chang, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2505.15779)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-feng.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **A High-Quality Dataset and Reliable Evaluation for Interleaved Image-Text Generation**
  - Yukang Feng<span style="color:red;">*</span>, Jianwen Sun<span style="color:red;">*</span>, `Chuanhao Li`, Zizhen Li, Jiaxin Ai, Fanrui Zhang, Yifan Chang, Sizhuo Zhou, Shenglin Zhang, Yu Dai, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2506.09427)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-sun.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **ARMOR: Empowering Autoregressive Multimodal Understanding Model with Interleaved Multimodal Generation via Asymmetric Synergy**
  - Jianwen Sun<span style="color:red;">*</span>, Yukang Feng<span style="color:red;">*</span>, `Chuanhao Li`, Fanrui Zhang, Zizhen Li, Jiaxin Ai, Sizhuo Zhou, Pengfei Zhou, Yu Dai, Shenglin Zhang, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2503.06542) [[code]](https://armor.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-zhou.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **MDK12-Bench: A Multi-Discipline Benchmark for Evaluating Reasoning in Multimodal Large Language Models**
  - Pengfei Zhou<span style="color:red;">*</span>, Fanrui Zhang<span style="color:red;">*</span>, Xiaopeng Peng<span style="color:red;">*</span>, Zhaopan Xu, Jiaxin Ai, Yansheng Qiu, `Chuanhao Li`, Zhen Li, Ming Li, Yukang Feng, Jianwen Sun, Haoquan Zhang, Zizhen Li, Xiaofeng Mao, Wangbo Zhao, Kai Wang, Xiaojun Chang, Wenqi Shao, Yang You<span style="color:blue;">+</span>, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2504.05782) [[code]](https://github.com/LanceZPF/MDK12)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">arXiv 2025</div><img src='images/thumbnail/2025-arxiv-chang.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **SridBench: Benchmark of Scientific Research Illustration Drawing of Image Generation Model**
  - Yifan Chang<span style="color:red;">*</span>, Yukang Feng<span style="color:red;">*</span>, Jianwen Sun<span style="color:red;">*</span>, Jiaxin Ai, `Chuanhao Li`, S. Kevin Zhou, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [arXiv 2025] [[paper]](https://arxiv.org/abs/2505.22126)
</div>
</div>


<span class='anchor' id='-lwzl'></span>

# 📝 Selected Publications
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/thumbnail/2025-emnlp-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **InMind: Evaluating LLMs in Capturing and Applying Individual Human Reasoning Styles**
  - Zizhen Li, `Chuanhao Li`, Yibin Wang, Qi Chen, Diping Song, Yukang Feng, Jianwen Sun, Jiaxin Ai, Fanrui Zhang, Mingzhu Sun, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [EMNLP 2025] [Main Conference] [[paper]]()
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IJCAI 2025</div><img src='images/thumbnail/2025-ijcai-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Multi-Sourced Compositional Generalization in Visual Question Answering**
  - `Chuanhao Li`<span style="color:red;">*</span>, Wenbo Ye<span style="color:red;">*</span>, Zhen Li, Yuwei Wu<span style="color:blue;">+</span>, and Yunde Jia.
  - [IJCAI 2025] [[paper]](https://arxiv.org/abs/2505.23045) [[code]](https://github.com/NeverMoreLCH/MSCG)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/thumbnail/2025-cvpr-zhou.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **GATE OpenING: A Comprehensive Benchmark for Judging Open-ended Interleaved Image-Text Generation**
  - Pengfei Zhou<span style="color:red;">*</span>, Xiaopeng Peng<span style="color:red;">*</span>, Jiajun Song, `Chuanhao Li`, Zhaopan Xu, Yue Yang, Ziyao Guo, Hao Zhang, Yuqi Lin, Yefei He, Lirui Zhao, Shuo Liu, Tianhua Li, Yuxuan Xie, Xiaojun Chang, Yu Qiao, Wenqi Shao, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [CVPR 2025] **[Oral] (Top 3.3%)** [[paper]](https://arxiv.org/abs/2411.18499) [[code]](https://opening-benchmark.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='images/thumbnail/2025-iclr-meng.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **MMIU: Multimodal Multi-image Understanding for Evaluating Large Vision-Language Models**
  - Fanqing Meng<span style="color:red;">*</span>, Jin Wang<span style="color:red;">*</span>, `Chuanhao Li`<span style="color:red;">*</span>, Quanfeng Lu, Hao Tian, Jiaqi Liao, Xizhou Zhu, Jifeng Dai, Yu Qiao, Ping Luo, Kaipeng Zhang<span style="color:blue;">+</span>, and Wenqi Shao<span style="color:blue;">+</span>.
  - [ICLR 2025] [[paper]](https://arxiv.org/abs/2408.02718) [[code]](https://mmiu-bench.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2025</div><img src='images/thumbnail/2025-aaai-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Consistency of Compositional Generalization across Multiple Levels**
  - `Chuanhao Li`<span style="color:red;">*</span>, Zhen Li<span style="color:red;">*</span>, Chenchen Jing<span style="color:blue;">+</span>, Xiaomeng Fan, Wenbo Ye, Yuwei Wu<span style="color:blue;">+</span>, and Yunde Jia.
  - [AAAI 2025] [[paper]](https://arxiv.org/abs/2412.13636) [[code]](https://github.com/NeverMoreLCH/CCG)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/thumbnail/2024-neurips-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **SearchLVLMs: A Plug-and-Play Framework for Augmenting Large Vision-Language Models by Searching Up-to-Date Internet Knowledge**
  - `Chuanhao Li`, Zhen Li, Chenchen Jing, Shuo Liu, Wenqi Shao, Yuwei Wu<span style="color:blue;">+</span>, Ping Luo, Yu Qiao, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [NeurIPS 2024] [[paper]](https://nips.cc/virtual/2024/poster/93813) [[code]](https://nevermorelch.github.io/SearchLVLMs.github.io/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2024</div><img src='images/thumbnail/2024-neurips-liu.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **ConvBench: A Multi-Turn Conversation Evaluation Benchmark with Hierarchical Capability for Large Vision-Language Models**
  - Shuo Liu, Kaining Ying, Hao Zhang, Yue Yang, Yuqi Lin, Tianle Zhang, `Chuanhao Li`, Yu Qiao, Ping Luo, Wenqi Shao<span style="color:blue;">+</span>, and Kaipeng Zhang<span style="color:blue;">+</span>.
  - [NeurIPS 2024] **[Spotlight]** [[paper]](https://arxiv.org/abs/2403.20194) [[code]](https://github.com/shirlyliu64/ConvBench)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECCV 2024</div><img src='images/thumbnail/2024-eccv-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Compositional Substitutivity of Visual Reasoning for Visual Question Answering**
  - `Chuanhao Li`<span style="color:red;">*</span>, Zhen Li<span style="color:red;">*</span>, Chenchen Jing<span style="color:blue;">+</span>, Yuwei Wu<span style="color:blue;">+</span>, Mingliang Zhai, and Yunde Jia.
  - [ECCV 2024] [[paper]](https://eccv.ecva.net/virtual/2024/poster/1492) [[code]](https://github.com/NeverMoreLCH/CG-SPS)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">EMNLP 2024</div><img src='images/thumbnail/2024-emnlp-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **In-Context Compositional Generalization for Large Vision-Language Models**
  - `Chuanhao Li`, Chenchen Jing, Zhen Li, Mingliang Zhai, Yuwei Wu<span style="color:blue;">+</span>, and Yunde Jia.
  - [EMNLP 2024] [Main Conference] [[paper]](https://aclanthology.org/2024.emnlp-main.996/)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">TOMM 2024</div><img src='images/thumbnail/2024-tomm-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Adversarial Sample Synthesis for Visual Question Answering**
  - `Chuanhao Li`, Chenchen Jing, Zhen Li, Yuwei Wu<span style="color:blue;">+</span>, and Yunde Jia.
  - [TOMM 2024] [[paper]](https://dl.acm.org/doi/10.1145/3688848)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2023</div><img src='images/thumbnail/2023-cvpr-li.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Exploring the Effect of Primitives for Compositional Generalization in Vision-and-Language**
  - `Chuanhao Li`, Zhen Li, Chenchen Jing<span style="color:blue;">+</span>, Yunde Jia, and Yuwei Wu<span style="color:blue;">+</span>.
  - [CVPR 2023] [[paper]](https://openaccess.thecvf.com/content/CVPR2023/html/Li_Exploring_the_Effect_of_Primitives_for_Compositional_Generalization_in_Vision-and-Language_CVPR_2023_paper.html) [[code]](https://github.com/NeverMoreLCH/SSL2CG)
</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">AAAI 2022</div><img src='images/thumbnail/2022-aaai-jing.png' alt="sym"></div></div>
<div class='paper-box-text' markdown="1">
  **Learning the Dynamics of Visual Relational Reasoning via Reinforced Path Routing**
  - Chenchen Jing, Yunde Jia, Yuwei Wu, `Chuanhao Li`, and Qi Wu.
  - [AAAI 2022] [[paper]](https://ojs.aaai.org/index.php/AAAI/article/view/19997)
</div>
</div>
    
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

