---
permalink: /
title: "Long Wei (魏龙)"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  /* 1. 基础布局：全宽内容区 + 缩小侧边栏（保留原有功能） */
  .page__content {
    max-width: 100% !important; /* 覆盖默认宽度，实现全宽 */
    width: 100% !important;     
    padding: 0 20px !important; /* 加左右内边距，避免文字贴边 */
  }
  .archive__content {
    max-width: 100% !important; /* 兼容archive类页面 */
  }
  .sidebar {
    max-width: 20% !important; /* 缩小侧边栏，给主内容更多空间 */
  }

  /* 2. 字体大小核心设置：标题显著大于正文（整合你的需求） */
  /* 正文：固定14px（清晰易读，与标题拉开差距） */
  .page__content p,        /* 普通段落正文 */
  .page__content li,        /* 列表项正文 */
  .page__content a,         /* 链接文字（避免链接大小不一致） */
  .page__content font       /* 论文中红色标注文字（如获奖信息） */
  {
    font-size: 14px !important; /* 固定像素，比标题小一半左右 */
    line-height: 1.6 !important; /* 优化行高，提升可读性 */
  }

  /* 标题：固定大小，确保显著大于正文 */
  .page__content h1 { /* 1级标题：# About Me 等 */
    font-size: 28px !important; /* 是正文的2倍，视觉突出 */
    margin: 1.8em 0 0.8em 0 !important; /* 上下间距，强化层级 */
    font-weight: 700 !important; /* 加粗，进一步区分正文 */
  }
  .page__content h2 { /* 2级标题（若后续添加） */
    font-size: 24px !important; /* 比正文大10px，仍显著突出 */
    margin: 1.5em 0 0.6em 0 !important;
    font-weight: 600 !important;
  }

  /* 3. 论文标题特殊处理（可选优化） */
  .page__content strong { /* 论文标题用了<strong>，避免与正文混淆 */
    font-size: 15px !important; /* 比正文略大1px，突出论文标题 */
    font-weight: 600 !important;
  }
</style>

# About Me
I am an incoming assistant professor in [Artificial Intelligence Innovation and Incubation (AI³) Institute](https://ai3.fudan.edu.cn/#) of [Fudan University](https://www.fudan.edu.cn/en/). Previously, I was a postdoctoral researcher from [Westlake University](https://en.westlake.edu.cn/), working with [Prof. Tailin Wu](https://tailin.org/). 
Before that, I worked at [Damo Academy, Alibaba Group](https://damo.alibaba.com/?language=en). 
I received my Ph.D. degree in Computer Science and Engineering from [Zhejiang University](https://www.zju.edu.cn/english/) in 2020, advised by [Prof. Xiaofei He](http://www.cad.zju.edu.cn/home/xiaofeihe/) and [Prof. Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/). I obtained my Bachelor's degree in Mathematics and Applied Mathematics from Zhejiang University in 2013.

# Research Interest

My research interests primarily lie in foundational and applied research at the intersection of AI and scientific domains. My long-term goal is to develop intelligent systems that rival the capabilities of human scientists and engineers, achieving breakthroughs in key challenges across science and engineering. Currently, I focus on the following directions:

- **Foundational Technologies in AI for Science**: (1) Efficient machine learning methods for scientific applications; (2) Universal approaches for complex systems modeling; (3) Development of agent systems to enable automated scientific discovery.

- **Applications of AI in Science**: (1) Leveraging AI to address simulation, design, and control problems in energy, embodied intelligence, and related fields; (2) Applying AI to tackle major challenges in healthcare and medical domains.

# Publications/Preprints [[Full list](https://scholar.google.com/citations?user=GU42ydUAAAAJ&hl=en)]
**Recent Advances on Machine Learning for Computational Fluid Dynamics: A Survey**  
Haixin Wang, Yadi Cao, Zijie Huang, Yuxuan Liu, Peiyan Hu, Xiao Luo, Zezheng Song, Wanjia Zhao, Jilin Liu, Jinan Sun, Shikun Zhang, **Long Wei**, Yue Wang, Tailin Wu, Zhi-Ming Ma, Yizhou Sun  
arXiv:2408.12171. [[PDF](https://arxiv.org/abs/2408.12171)]

**From Uncertain to Safe: Conformal Fine-Tuning of Diffusion Models for Safe PDE Control**  
Peiyan Hu, Xiaowei Qian, Wenhao Deng, Rui Wang, Haodong Feng, Ruiqi Feng, Tao Zhang, **Long Wei**, Yue Wang, Zhi-Ming Ma, Tailin Wu. 
Forty-Second International Conference on Machine Learning (ICML), 2025. [[PDF](https://arxiv.org/pdf/2502.02205)]

**CL-DiffPhyCon: Closed-loop Diffusion Control of Complex Physical Systems**  
**Long Wei**<sup>\*</sup>, Haodong Feng<sup>\*</sup>, Yuchen Yang, Ruiqi Feng, Peiyan Hu, Xiang Zheng, Tao Zhang, Dixia Fan, Tailin Wu  
International Conference on Learning Representations (ICLR), 2025. [[PDF](https://arxiv.org/pdf/2408.03124)][[Code](https://github.com/AI4Science-WestlakeU/CL_DiffPhyCon)] <font color="red"> Nomination of Outstanding Youth Paper Award </font> at [[China Embodied AI Conference (CEAI) 2025](https://ceai.caai.cn/)]

**DiffPhyCon: A Generative Approach to Control Complex Physical Systems**  
**Long Wei**<sup>\*</sup>, Peiyan Hu<sup>\*</sup>, Ruiqi Feng<sup>\*</sup>, Yixuan Du, Tao Zhang, Rui Wang, Yue Wang, Zhi-Ming Ma, Tailin Wu   
Thirty-eighth Annual Conference on Neural Information Processing Systems (NeurIPS) 2024. [[PDF](https://web3.arxiv.org/abs/2407.06494)][[Code](https://github.com/AI4Science-WestlakeU/diffphycon)]

**Generative PDE Control**  
**Long Wei**<sup>\*</sup>, Peiyan Hu<sup>\*</sup>, Ruiqi Feng<sup>\*</sup>, Yixuan Du, Tao Zhang, Rui Wang, Yue Wang, Zhi-Ming Ma, Tailin Wu   
[[ICLR 2024 Workshop on AI4DifferentialEquations In Science](https://ai4diffeqtnsinsci.github.io/schedule)] (<font color="red">Oral</font>). [[PDF](https://openreview.net/forum?id=vaKnCahjdj)][[Code](https://github.com/AI4Science-WestlakeU/diffphycon)]

**Compositional Generative Inverse Design**  
Tailin Wu<sup>\*</sup>, Takashi Maruyama<sup>\*</sup>, **Long Wei**<sup>\*</sup>, Tao Zhang<sup>\*</sup>, Yilun Du<sup>\*</sup>, Gianluca Iaccarino, Jure Leskovec   
International Conference on Learning Representations (ICLR), 2024 (<font color="red">Spotlight</font>). [[PDF](https://openreview.net/forum?id=wmX0CqFSd7)][[Code](https://github.com/AI4Science-WestlakeU/cindm)]

**SIF: Self-inspirited feature learning for person re-identification**  
**Long Wei**, Zhenyong Wei, Zhongming Jin, Zhengxu Yu, Jianqiang Huang, Deng Cai, Xiaofei He, Xian-Sheng Hua  
IEEE Transactions on Image Processing, 29, 4942-4951, 2020. [[PDF](https://www.researchgate.net/profile/Long-Wei-14/publication/339700962_SIF_Self-Inspirited_Feature_Learning_for_Person_Re-Identification/links/64b1eed3c41fb852dd70eb7b/SIF-Self-Inspirited-Feature-Learning-for-Person-Re-Identification.pdf)]  

**Decouple co-adaptation: Classifier randomization for person re-identification**  
**Long Wei**, Zhenyong Wei, Zhongming Jin, Qianxiao Wei, Jianqiang Huang, Xian-Sheng Hua, Deng Cai, Xiaofei He  
Neurocomputing, 383, 1-9, 2020.
