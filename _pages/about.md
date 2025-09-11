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
    font-size: 15px !important; /* 固定像素，比标题小一半左右 */
    line-height: 1.6 !important; /* 优化行高，提升可读性 */
  }

  /* 标题：固定大小，确保显著大于正文 */
  .page__content h1 { /* 1级标题：# About Me 等 */
    font-size: 24px !important; /* 是正文的2倍，视觉突出 */
    margin: 1.8em 0 0.8em 0 !important; /* 上下间距，强化层级 */
    font-weight: 700 !important; /* 加粗，进一步区分正文 */
  }
  .page__content h2 { /* 2级标题（若后续添加） */
    font-size: 20px !important; /* 比正文大10px，仍显著突出 */
    margin: 1.5em 0 0.6em 0 !important;
    font-weight: 600 !important;
  }

  /* 3. 论文标题特殊处理（可选优化） */
  .page__content strong { /* 论文标题用了<strong>，避免与正文混淆 */
    font-size: 15px !important; /* 比正文略大1px，突出论文标题 */
    font-weight: 600 !important;
  }
</style>

<!-- # About Me -->
I am an incoming assistant professor at the [Artificial Intelligence Innovation and Incubation (AI³) Institute](https://ai3.fudan.edu.cn/#) (人工智能创新与产业研究院) of [Fudan University](https://www.fudan.edu.cn/en/) ([复旦大学](https://www.fudan.edu.cn/)). Previously, I was a postdoctoral researcher at [Westlake University](https://en.westlake.edu.cn/) ([西湖大学](https://www.westlake.edu.cn/)), working with [Prof. Tailin Wu](https://tailin.org/). 
Before that, I worked at [Damo Academy, Alibaba Group](https://damo.alibaba.com/?language=en) ([阿里巴巴达摩院](https://damo.alibaba.com/?language=zh)). 
I received my Ph.D. degree in Computer Science and Engineering from [Zhejiang University](https://www.zju.edu.cn/english/) ([浙江大学](https://www.zju.edu.cn/)) in 2020, advised by [Prof. Xiaofei He](http://www.cad.zju.edu.cn/home/xiaofeihe/) and [Prof. Deng Cai](http://www.cad.zju.edu.cn/home/dengcai/). During my doctoral studies, I was a joint PhD student in the group of [Prof. Jieping Ye](http://www.yelabs.net/) at the University of Michigan, Ann Arbor. Earlier, I completed my Bachelor's degree in Mathematics and Applied Mathematics at Zhejiang University in 2013.

I am actively recruiting for multiple positions to join our research, including postdoctoral researchers, research assistants, Ph.D. students (Fall 2026), and master’s students (Fall 2026). We also welcome applications for research internships (open to undergraduate/master/doctoral students, and individuals on a gap year).
If you have a strong motivation for exploring interdisciplinary research at the intersection of AI and science, as outlined in the following Research Interests section, please do not hesitate to contact me.

# Research Interests

My research interests primarily lie in the intersection of AI and scientific domains. My long-term objective is to develop intelligent systems that match the problem-solving capabilities of human scientists and engineers, achieving breakthroughs in key challenges across science and engineering. Currently, I focus on the following directions:

- **AI for Science Foundational Research**: (1) Efficient machine learning algorithms for scientific problems; (2) Universal approaches for modeling and computing complex systems (e.g., physical, biological, or engineering systems) that generalize across diverse domains; (3) Design of autonomous agent systems to enable automated scientific discovery.

- **AI for Science Applications**: (1) Developing AI methods to solve simulation, design, and control challenges in energy systems, embodied intelligence, and other critical engineering domains; (2) Applying AI methods to tackle major challenges in healthcare and medical domains.

# News
- 2025/04 Our paper [*Wavelet Diffusion Neural Operator*](https://openreview.net/forum?id=FQhDIGuaJ4) is featured by [集智俱乐部](https://mp.weixin.qq.com/s/s7jVimP2lQdGlOn1q7DkHg).  
- 2025/03 Our paper [*CL-DiffPhyCon*](https://openreview.net/forum?id=PiHGrTTnvb) is nominated for the Outstanding Youth Paper Award at the China Embodied AI Conference (CEAI 2025). Thanks to all the collaborators!
- 2025/02 Our paper [*CL-DiffPhyCon*](https://openreview.net/forum?id=PiHGrTTnvb) is featured by [机器之心](https://mp.weixin.qq.com/s/nlnNMrJBCwPrf38k4uKKTA).  
- 2025/01 I am awarded the 2024 Outstanding Postdoc Award of Westlake University.  
- 2024/12 Our paper [*DiffPhyCon*](https://openreview.net/forum?id=MbZuh8L0Xg) is featured by [集智俱乐部](https://mp.weixin.qq.com/s/xV8GydA51Jc3OruWSUSRmA).  
- 2024/10 I am supported by the Zhejiang Province Outstanding Postdoctoral Funding Program (China).
- 2024/05 I give an Oral Presentation on our paper [*Generative PDE Control*](https://openreview.net/forum?id=vaKnCahjdj) at [ICLR 2024 Workshop on AI4DifferentialEquations in Science](https://ai4diffeqtnsinsci.github.io/schedule).


# Selected Publications/Preprints 
<!-- # [[Full list](https://scholar.google.com/citations?user=GU42ydUAAAAJ&hl=en)] -->
<img src="path/to/fluidzero-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**FluidZero: Mastering Diverse Tasks in Fluid Systems through a Single Generative Model**  
Haodong Feng, Haoren Zheng, Peiyan Hu, Hongyuan Liu, Chenglei Yu, **Long Wei**, Ruiqi Feng, Jinlong Duan, Dixia Fan, Tailin Wu. [[PDF](https://assets-eu.researchsquare.com/files/rs-6881567/v2_covered_108cb63b-c349-4b40-9e71-b2f1dffc28a9.pdf?c=1750707611)]  
<div style="clear: both;"></div>

<img src="path/to/recent-advances-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**Recent Advances on Machine Learning for Computational Fluid Dynamics: A Survey**  
Haixin Wang, Yadi Cao, Zijie Huang, Yuxuan Liu, Peiyan Hu, Xiao Luo, Zezheng Song, Wanjia Zhao, Jilin Liu, Jinan Sun, Shikun Zhang, **Long Wei**, Yue Wang, Tailin Wu, Zhi-Ming Ma, Yizhou Sun  
arXiv:2408.12171. [[PDF](https://arxiv.org/abs/2408.12171)]  
<div style="clear: both;"></div>

<img src="safepde-thumbnail.png" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**From Uncertain to Safe: Conformal Fine-Tuning of Diffusion Models for Safe PDE Control**  
Peiyan Hu, Xiaowei Qian, Wenhao Deng, Rui Wang, Haodong Feng, Ruiqi Feng, Tao Zhang, **Long Wei**, Yue Wang, Zhi-Ming Ma, Tailin Wu. 
ICML 2025. [[PDF](https://arxiv.org/pdf/2502.02205)]  
<div style="clear: both;"></div>

<img src="path/to/cl-diffphycon-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**CL-DiffPhyCon: Closed-loop Diffusion Control of Complex Physical Systems**  
**Long Wei**<sup>\*</sup>, Haodong Feng<sup>\*</sup>, Yuchen Yang, Ruiqi Feng, Peiyan Hu, Xiang Zheng, Tao Zhang, Dixia Fan, Tailin Wu  
ICLR 2025. [[PDF](https://arxiv.org/pdf/2408.03124)][[Code](https://github.com/AI4Science-WestlakeU/CL_DiffPhyCon)] 
<font color="red"> Nomination of Outstanding Youth Paper Award </font> at [China Embodied AI Conference (CEAI) 2025](https://ceai.caai.cn/)  
<div style="clear: both;"></div>

<img src="path/to/diffphycon-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**DiffPhyCon: A Generative Approach to Control Complex Physical Systems**  
**Long Wei**<sup>\*</sup>, Peiyan Hu<sup>\*</sup>, Ruiqi Feng<sup>\*</sup>, Yixuan Du, Tao Zhang, Rui Wang, Yue Wang, Zhi-Ming Ma, Tailin Wu   
NeurIPS 2024. [[PDF](https://web3.arxiv.org/abs/2407.06494)][[Code](https://github.com/AI4Science-WestlakeU/diffphycon)]  
<div style="clear: both;"></div>

<img src="path/to/generative-pde-control-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**Generative PDE Control**  
**Long Wei**<sup>\*</sup>, Peiyan Hu<sup>\*</sup>, Ruiqi Feng<sup>\*</sup>, Yixuan Du, Tao Zhang, Rui Wang, Yue Wang, Zhi-Ming Ma, Tailin Wu   
[ICLR 2024 Workshop on AI4DifferentialEquations In Science](https://ai4diffeqtnsinsci.github.io/schedule) (<font color="red">Oral</font>). [[PDF](https://openreview.net/forum?id=vaKnCahjdj)][[Code](https://github.com/AI4Science-WestlakeU/diffphycon)]  
<div style="clear: both;"></div>

<img src="path/to/compositional-generative-inverse-design-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**Compositional Generative Inverse Design**  
Tailin Wu<sup>\*</sup>, Takashi Maruyama<sup>\*</sup>, **Long Wei**<sup>\*</sup>, Tao Zhang<sup>\*</sup>, Yilun Du<sup>\*</sup>, Gianluca Iaccarino, Jure Leskovec   
ICLR 2024 (<font color="red">Spotlight</font>). [[PDF](https://openreview.net/forum?id=wmX0CqFSd7)][[Code](https://github.com/AI4Science-WestlakeU/cindm)]  
<div style="clear: both;"></div>

<img src="path/to/sif-thumbnail.jpg" alt="" style="float: left; margin-right: 20px; width: 150px; height: auto; margin-bottom: 20px;">  
**SIF: Self-inspirited Feature Learning for Person Re-identification**  
**Long Wei**, Zhenyong Wei, Zhongming Jin, Zhengxu Yu, Jianqiang Huang, Deng Cai, Xiaofei He, Xian-Sheng Hua  
IEEE Transactions on Image Processing (TIP), 29, 4942-4951, 2020. [[PDF](https://www.researchgate.net/profile/Long-Wei-14/publication/339700962_SIF_Self-Inspirited_Feature_Learning_for_Person_Re-Identification/links/64b1eed3c41fb852dd70eb7b/SIF-Self-Inspirited-Feature-Learning-for-Person-Re-Identification.pdf)]  
<div style="clear: both;"></div>