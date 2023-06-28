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

<!-- Hi! My name is Yijie Lin.  -->
I’m a Ph.D. student from College of Computer Science, Sichuan Univerisity, advised by Prof.[Xi Peng](http://pengxi.me). I am now a research intern at Ant Group, doing video-language pretraining.

My research interests mainly focus on Multi-modal Learning and Multi-view Learning, especially the applications in open scenarios, e.g., missing modality and noisy correspondence.
<!-- (sentence-visual pairs). -->

<!-- My research interests include Multimodal Learning and Unsupervised Learning, which can be unified to the framework of Representation Learning. -->

<!-- My research interest includes neural machine translation and computer vision. I have published more than 100 papers at the top international AI conferences with total <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'>google scholar citations <strong><span id='total_cit'>260000+</span></strong></a> (You can also use google scholar badge <a href='https://scholar.google.com/citations?user=DhtAFkwAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>). -->


# 🔥 News
<!-- - *2022.02*: &nbsp;🎉🎉 Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
- *2022.10*: &nbsp; One paper was accepted at Findings of EMNLP 2022.
- *2022.08*: &nbsp; One paper was accepted by IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)!
- *2022.05*: &nbsp; One paper was accepted by IEEE Transactions on Image Processing  (TIP).
- *2021.03*: &nbsp; One paper was accepted by IEEE Conference on Computer Vision and Pattern Recognition (CVPR 2021), Virtual-only Conference, Jun, 2021.

# 📝 Publications 


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2021, TPAMI 2022</div><img src='images/papers/completer.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[COMPLETER: Incomplete Multi-view Clustering via Contrastive Prediction](https://openaccess.thecvf.com/content/CVPR2021/papers/Lin_COMPLETER_Incomplete_Multi-View_Clustering_via_Contrastive_Prediction_CVPR_2021_paper.pdf), **Yijie Lin**, Yuanbiao Gou, Zitao Liu, Boyun Li, Jiancheng Lv, Xi Peng


<a href="https://www.bilibili.com/video/BV1Ub4y1a7Zy?spm_id_from=333.337.search-card.all.click&vd_source=c4896e9b68d2c7a283fe99a0899df781"><strong>Video</strong></a>
\|
<a href="https://cs.scu.edu.cn/info/1246/15640.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2021-CVPR-Completer"><strong>Code</strong></a>
<!-- **Code**  -->
[![](https://img.shields.io/github/stars/XLearning-SCU/2021-CVPR-Completer?style=social&label=Stars)](https://github.com/XLearning-SCU/2021-CVPR-Completer)
<!-- <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong> -->
<strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:d1gkVwhDpl0C'></span></strong>
<!-- https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=KXKVYHsAAAAJ:d1gkVwhDpl0C -->


[Dual Contrastive Prediction for Incomplete Multi-view Representation Learning](http://pengxi.me/wp-content/uploads/2023/02/DCP-2023_compressed.pdf),  **Yijie Lin**, Yuanbiao Gou, Xiaotian Liu, Jinfeng Bai, Jiancheng Lv, Xi Peng

<a href="https://cs.scu.edu.cn/info/1246/17111.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2022-TPAMI-DCP"><strong>Code</strong></a>
[![](https://img.shields.io/github/stars/XLearning-SCU/2022-TPAMI-DCP?style=social&label=Stars)](https://github.com/XLearning-SCU/2022-TPAMI-DCP)
<strong><span class='show_paper_citations' data='KXKVYHsAAAAJ:UeHWp8X0CEIC'></span></strong>
</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Tech report</div><img src='images/papers/common.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Graph Matching with Bi-level Noisy Correspondence](https://arxiv.org/pdf/2212.04085),  **Yijie Lin**, Mouxing Yang, Jun Yu, Peng Hu, Changqing Zhang, Xi Peng

Reveal the noisy correspondence problem in graph matching

</div></div>


<!-- - `TPAMI 2022` [Dual Contrastive Prediction for Incomplete Multi-view Representation Learning](http://pengxi.me/wp-content/uploads/2023/02/DCP-2023_compressed.pdf),  **Yijie Lin**, Yuanbiao Gou, Xiaotian Liu, Jinfeng Bai, Jiancheng Lv, Xi Peng
\|
<a href="https://cs.scu.edu.cn/info/1246/17111.htm"><strong>中文简介</strong></a>
\|
<a href="https://github.com/XLearning-SCU/2022-TPAMI-DCP"><strong>Code</strong></a> -->


- `EMNLP Findings 2022` [Improve Interpretability of Neural Networks via Sparse Contrastive Coding](https://aclanthology.org/2022.findings-emnlp.32.pdf), Junhong Liu\*,
**Yijie Lin**\*, Liang Jiang, Jia Liu, Zujie Wen, Xi Peng

- `TNNLS 2023` [Single-cell RNA-seq Debiased Clustering via Batch Effect Disentanglement](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=10086540), Yunfan Li, **Yijie Lin**, Han Luo, Peng Hu, Dezhong Peng, Xi Peng 

- `TIP 2022`  [Unsupervised Neural Rendering for Image Hazing](https://ieeexplore.ieee.org/document/9788526/), Boyun Li, **Yijie Lin**, Xiao Liu, Peng Hu, Jiancheng Lv, Xi Peng




<!-- under review -->

# 🎖 Honors and Awards
- *2022.11* [Huawei Scholarship at Sichuan University](https://ygb.scu.edu.cn/info/1007/2515.htm) (First prize)
- *2021.10* Innovation Scholarship (Ph.D. student) 
- *2019.09* [National Scholarship](http://www.moe.gov.cn/srcsite/A05/s7505/201912/t20191217_412368.html) (Undergraduate, Top 1%)


<!-- # 📖 Educations
- 2020.09 - now, Ph.D. student, Sichuan Univeristy, Chengdu.
- 2016.09 - 2020.06, Undergraduate, Sichuan Univeristy, Chengdu. -->


<!-- 
# 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)


# 💻 
-->
# 🙋 Service
<!-- - *2019.05 - 2020.02*, [Lorem](https://github.com/), China.  -->

<!-- - Journal Reviewer of IEEE Transactions on Knowledge and Data Engineering, IEEE Transactions on Neural Networks and Learning Systems, IEEE Transactions on Systems, Man and Cybernetics: Systems. -->
- *Journal Reviewer*: IEEE TKDE, IEEE TNNLS, IEEE TCYB, IEEE TSMC, Machine Learning, Neural Networks.

- *Conference Reviewer*: ICLR, NeurIPS, ICML, ICCV, AAAI.
<!-- - Conference Reviewer: of ICLR 2023, NeurIPS 2023, ICML 2023, ICCV 2023, AAAI 2023. -->
<!-- , CICAI 2021-2022, ICIG 2021, ACML 2021, PRCV 2021-2022 -->

<!-- 
# 💬 Talks ~
 -->

