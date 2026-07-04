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

# 😃 About me
I'm a Ph.D. student at <a href="http://sanctusfactory.com/u-aim/" style="color: #7289da; text-decoration:none">**Artificial Intelligence & Machine Learning (U-AIM) Lab.**</a>  in KAIST, under the supervision of Prof. Chang D. Yoo. My primary research interests focus on the application of generative models in the field of computer vision. Starting from image/video generation and editing, I have recently been focusing on 3D/4D generation and reconstruction. My long-term goal is to integrate these directions toward building generative world models that can perceive, reconstruct, and simulate the 3D world.
<!-- and real-time processing for enhanced user experience. -->


<!-- (Expected graduation date: 2024.08). -->

My research interest includes: 
- 3D/4D Reconstruction, Generation
- World Models and Simulation

# 🔥 News

<ul>
<li><em>2026.06</em>: &nbsp;🎉 Two papers accepted to ECCV 2026</li>
<li><em>2026.05</em>: &nbsp;🎉 One paper accepted to ICML 2026</li>
<li><em>2026.03</em>: &nbsp;🏆 Received the Outstanding Research Achievement Award from KAIST Electrical Engineering.</li>
</ul>

<div id="more-news" style="display:none;">
<ul>
<li><em>2026.02</em>: &nbsp;🎉 One paper accepted to CVPR 2026</li>
<li><em>2025.09</em>: &nbsp;🚀 I started a research internship at <a href="https://www.naverlabs.com/" style="color:rgb(0, 0, 0); text-decoration:none"><strong>NAVER LABS</strong></a> (Spatial AI team)</li>
<li><em>2025.06</em>: &nbsp;🎉 One paper accepted to ICCV 2025</li>
<li><em>2025.06</em>: &nbsp;🎉 I am recognized as an <span style="color:darkred"><strong>outstanding reviewer (top 5.64%)</strong></span> for CVPR 2025</li>
<li><em>2025.05</em>: &nbsp;🎉 One paper accepted to ICML 2025 <span style="color:darkred"><strong>(Spotlight, top 2.6%)</strong></span></li>
</ul>
</div>

<button id="news-toggle" onclick="var m=document.getElementById('more-news');if(m.style.display==='none'){m.style.display='block';this.textContent='Show less ▲';}else{m.style.display='none';this.textContent='Show more ▼';}" style="background:none;border:1px solid #7289da;color:#7289da;border-radius:4px;padding:3px 12px;cursor:pointer;font-size:0.85em;">Show more ▼</button>

# 📝 Conference Publications 
## 2026

<div class='paper-box'><div class='paper-box-image'><div class="badge">ECCV 2026</div><img src='images/ECCV_2026_InSpace.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C14] InSpace: Structure-Aware 3D Indoor Scene Generation from a Single 360° Image**

<span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, <a href="https://blandocs.github.io/" style="color: #7289da; text-decoration: none;">Hyunsu Kim</a>, Youngji Kim, Taejae Lee, <a href="https://siw00-lim.github.io/" style="color: #7289da; text-decoration: none;">Siwoo Lim</a>, <a href="https://dbstjswo505.github.io/" style="color: #7289da; text-decoration: none;">Sunjae Yoon</a>, Suyong Yeon<sup>†</sup>, <a href="https://sanctusfactory.com/family.php" style="color: #7289da; text-decoration: none;">Chang D. Yoo</a><sup>†</sup>

<span style="color:darkred">**ECCV**</span> 2026

<a href="https://kookie12.github.io/InSpace-Project-Page" class="paper-btn">Project Page</a> 

<span style="font-size: 0.85em; color: gray;">*Work done during the internship at NAVER LABS</span>

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">ECCV 2026</div><img src='images/ECCV_2026_tango.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C13] TanGO: Training-Free 3D Editing via Tangent-Space Guidance and Optimization**

<a href="https://siw00-lim.github.io/" style="color: #7289da; text-decoration: none;">Siwoo Lim</a>, <a href="https://dbstjswo505.github.io/" style="color: #7289da; text-decoration: none;">Sunjae Yoon</a>, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Hyeonseo Yun, <a href="https://sanctusfactory.com/family.php" style="color: #7289da; text-decoration: none;">Chang D. Yoo</a>

<span style="color:darkred">**ECCV**</span> 2026

<a href="https://siw00-lim.github.io/TanGO-Project-Page/" class="paper-btn">Project Page</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">ICML 2026</div><img src='images/ICML_2026_GADA.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C12] GADA: Geometry-Aware Deformable Aggregation for Image-Based Gaussian Splatting**

<a href="https://siw00-lim.github.io/" style="color: #7289da; text-decoration: none;">Siwoo Lim</a>, <a href="https://dbstjswo505.github.io/" style="color: #7289da; text-decoration: none;">Sunjae Yoon</a>, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, <a href="https://sanctusfactory.com/family.php" style="color: #7289da; text-decoration: none;">Chang D. Yoo</a>

<span style="color:darkred">**ICML**</span> 2026

<a href="https://arxiv.org/abs/2607.00595" class="paper-btn">Paper</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">CVPR 2026</div><img src='images/CVPR_2026_PDCR.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C11] PDCR: Perception-Decomposed Confidence Reward for Vision-Language Reasoning**

<a href="https://hee-suk-yoon.github.io/" style="color: #7289da; text-decoration: none;">Hee Suk Yoon</a>, <a href="https://esyoon7.github.io/" style="color: #7289da; text-decoration: none;">Eunseop Yoon</a>, <a href="https://jiwoohong93.github.io/" style="color: #7289da; text-decoration: none;">Ji Woo Hong</a>, <a href="https://eomsoohwan.github.io/" style="color: #7289da; text-decoration: none;">SooHwan Eom</a>, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Mark A. Hasegawa-Johnson, Qi Dai, Chong Luo, <a href="https://sanctusfactory.com/family.php" style="color: #7289da; text-decoration: none;">Chang D. Yoo</a>

<span style="color:darkred">**CVPR**</span> 2026

<a href="https://arxiv.org/abs/2605.13467" class="paper-btn">Paper</a> 

</div>
</div>

## 2025 
<div class='paper-box'><div class='paper-box-image'><div class="badge">ICCV 2025</div><img src='images/iccv2025_osd.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C10] Occlusion-robust Stylization for Drawing-based 3D Animation**

Sunjae Yoon, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Younghwan Lee, Ji Woo Hong, Chang D. Yoo

<span style="color:darkred">**ICCV**</span> 2025, <span style="color:darkred">**Review Score: 6,6,5 (avg. 5.67/6)**</span>

<a href="https://arxiv.org/abs/2508.00398" class="paper-btn">Paper</a> 
<a href="https://github.com/dbstjswo505/OSF" class="paper-btn">Code</a> 
<a href="https://dbstjswo505.github.io/Drawing-based-3D-Animation-page/" class="paper-btn">Project Page</a> 


</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">ICML 2025</div><img src='images/ICML_2025_FlowDrag.png' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C9] FlowDrag: 3D-aware Drag-based Image Editing with Mesh-guided Deformation Vector Flow Fields**

<span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Sunjae Yoon, Younghwan Lee, Ji Woo Hong, Chang D. Yoo

<span style="color:darkred">**ICML**</span> 2025, <span style="color:darkred">**Spotlight (313/12107=2.6%)**</span>

<a href="https://arxiv.org/abs/2507.08285" class="paper-btn">Paper</a> 
<a href="https://github.com/kookie12/FlowDrag" class="paper-btn">Code</a> 
<a href="https://kookie12.github.io/FlowDrag-Projecct-Page/" class="paper-btn">Project Page</a> 
<a href="https://icml.cc/media/PosterPDFs/ICML%202025/43848.png?t=1752477709.4670188" class="paper-btn">Poster</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">CVPR 2025</div><img src='images/ITA-MDT_2025.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C8] ITA-MDT: Image-Timestep-Adaptive Masked Diffusion Transformer Framework for Image-Based Virtual Try-On**

Ji Woo Hong, Tri Ton, Trung X. Pham, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Sunjae Yoon, Chang D. Yoo

<span style="color:darkred">**CVPR**</span> 2025

<a href="https://arxiv.org/abs/2503.20418" class="paper-btn">Paper</a> 
<a href="https://github.com/jiwoohong93/ita-mdt_code" class="paper-btn">Code</a> 
<a href="https://jiwoohong93.github.io/ita-mdt/" class="paper-btn">Project Page</a> 

</div>
</div>

## 2024

<div class='paper-box'><div class='paper-box-image'><div class="badge">NeurIPS 2024</div><img src='images/TPC_NeurIPS_2024.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C7] TPC: Test-time Procrustes Calibration for Diffusion-based Human Image Animation**

Sunjae Yoon, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Younghwan Lee, Chang D. Yoo

<span style="color:darkred">**NeurIPS**</span> 2024

<a href="https://arxiv.org/abs/2410.24037" class="paper-btn">Paper</a> 
<a href="https://github.com/dbstjswo505/TPC" class="paper-btn">Code</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">EMNLP 2024</div><img src='images/EMNLP_2024.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C6] Query-based Cross-Modal Projector Bolstering Mamba Multimodal LLM**

SooHwan Eom, Jay Shim, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Haebin Na, Mark A. Hasegawa-Johnson, Sungwoong Kim, Chang D. Yoo

<span style="color:darkred">**EMNLP**</span> 2024 (Findings)

<a href="https://aclanthology.org/2024.findings-emnlp.827/" class="paper-btn">Paper</a> 

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div class="badge">ECCV 2024</div><img src='images/FlexiEdit.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C5] FlexiEdit: Frequency-Aware Latent Refinement for Enhanced Non-Rigid Editing**

<span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Sunjae Yoon, Ji Woo Hong, Chang D. Yoo  

<span style="color:darkred">**ECCV**</span> 2024

<a href="https://arxiv.org/abs/2407.17850" class="paper-btn">Paper</a> 
<a href="https://github.com/kookie12/FlexiEdit" class="paper-btn">Code</a> 
<a href="https://kookie12.github.io/FlexiEdit-Project-Page" class="paper-btn">Project Page</a> 
<a href="https://eccv2024.ecva.net/media/PosterPDFs/ECCV%202024/666.png?t=1726421397.177207" class="paper-btn">Poster</a> 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div class="badge">ECCV 2024</div><img src='images/DNI.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C4] Dilutional Noise Initialization for Dilution Video Editing**

Sunjae Yoon, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Ji Woo Hong, Chang D. Yoo

<span style="color:darkred">**ECCV**</span> 2024

<a href="https://arxiv.org/abs/2409.13037v1" class="paper-btn">Paper</a> 
<a href="https://github.com/dbstjswo505/DNI" class="paper-btn">Code</a> 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div class="badge">ICML 2024</div><img src='images/FRAG.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C3] FRAG: Frequency Adapting Group for Diffusion Video Editing**

Sunjae Yoon, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Geonwoo Kim, Chang D. Yoo

<span style="color:darkred">**ICML**</span> 2024

<a href="https://icml.cc/virtual/2024/poster/34145" class="paper-btn">Paper</a> 
<a href="https://github.com/dbstjswo505/FRAG" class="paper-btn">Code</a> 
<a href="https://dbstjswo505.github.io/FRAG-page/" class="paper-btn">Project Page</a> 

</div>
</div>


<div class='paper-box'><div class='paper-box-image'><div class="badge">ICASSP 2024</div><img src='images/FreqOpt.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">

**[C2] Wavelet-Guided Acceleration of Text Inversion in Diffusion-Based Image Editing**

<span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Sunjae Yoon, Chang D. Yoo

<span style="color:darkred">**ICASSP**</span> 2024

<a href="https://arxiv.org/abs/2401.09794" class="paper-btn">Paper</a> 

</div>
</div>

## 2023

<div class='paper-box'><div class='paper-box-image'><div class="badge">ICCV 2023</div><img src='images/SCANet.jpg' alt="sym" width="100%"></div>
<div class='paper-box-text' markdown="1">


**[C1] SCANet: Scene Complexity Aware Network for Weakly-Supervised Video Moment Retrieval**

Sunjae Yoon, <span style="color: #00369F; text-decoration: none;">**Gwanhyeong Koo**</span>, Dahyun Kim, Chang D. Yoo

<span style="color:darkred">**ICCV**</span> 2023

<a href="https://openaccess.thecvf.com/content/ICCV2023/papers/Yoon_SCANet_Scene_Complexity_Aware_Network_for_Weakly-Supervised_Video_Moment_Retrieval_ICCV_2023_paper.pdf" class="paper-btn">Paper</a> 
<a href="https://github.com/dbstjswo505/SCANet" class="paper-btn">Code</a> 

<!-- [**Project**](https://scholar.google.com/citations?view_op=view_citation&hl=zh-CN&user=DhtAFkwAAAAJ&citation_for_view=DhtAFkwAAAAJ:ALROH1vI_8AC) <strong><span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span></strong>
- Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  -->
</div>
</div>


<!-- - **DiffusionNAG: Task-guided Neural Architecture Generation with Diffusion Models** \\
<a href="https://arxiv.org/abs/2305.16943" class="paper-btn">Paper</a> \\
<u>Sohyun An*</u>, Hayeon Lee\*, Jaehyeong Jo, Seanie Lee, Sung Ju Hwang (\*: equal contribution) \\
<span style="color:darkred">**Arxiv**</span>  -->

<!-- - [Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet](https://github.com), A, B, C, **CVPR 2020** -->

<!-- <a href="https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer" style="color: #7289da; text-decoration:none">**CVPR Outstanding Reviewer (2025)**</a> -->

# 💼 Work Experience

<div style="display:flex; align-items:center; flex-wrap:wrap; padding:1.5em 0; border-bottom:1px #efefef solid;">
<div style="flex:0 0 160px; display:flex; justify-content:center;">
<img src='images/naver_labs.png' alt="NAVER LABS" style="max-width:140px; width:100%;">
</div>
<div style="flex:1; padding-left:1.5em; min-width:240px;" markdown="1">

**Research Intern** @ <a href="https://www.naverlabs.com/" style="color: #7289da; text-decoration: none;">NAVER LABS</a> — Spatial AI Team

<span style="color:gray;">*2025.09 - 2026.03 · Seongnam-si, South Korea*</span>

Mentor: Suyong Yeon

</div>
</div>


# 🎖 Honors and Awards
- *2026.03* Received the Outstanding Research Achievement Award from KAIST Electrical Engineering.
- *2025.06* <a href="https://cvpr.thecvf.com/Conferences/2025/ProgramCommittee#all-outstanding-reviewer" style="color: #7289da; text-decoration:none">**CVPR Outstanding Reviewer (2025)**</a>, Recognized as one of the top 5.64% among 12,582 reviewers for CVPR 2025
- *2024.10* **1st Prize** 2nd Seoul National University Bundang Hospital (SNUBH) Datathon Award
- *2023.11* **Best Paper Award**, Winter Conference, Korean Artificial Intelligence Association (JKAIA), 2023
- *2022.09* TensorFlow Developer Certificate
- *2019.10* **Bronze Award** in 2019 International University Student	Creative Car Competition, in Autonomous	Driving

# 📖 Educations
- *2024.09 - Present*, **Ph.D.** in Electrical Engineering. (KAIST)
- *2023.03 - 2024.08*, **M.S.** in Electrical Engineering (Devision of Future Vehicle). (KAIST)
- *2017.03 - 2023.02*, **B.S.** in Electric Engineering. (DGIST)    

# 🎯 Projects
- *2023 - 2025*, Oriented Object Detection in Optical Remote Sensing Image, **Hanwha Systems**

# 🎨 Academic Services
- Conference Reviewer: ECCV'24, ICASSP'25, CVPR'25, ICML'25, SIGGRAPH'25, ACM MM'25, NeurIPS'25, WACV'26, AAAI'26, ICLR'26, ICASSP'26, CVPR'26, ECCV'26, SIGGRAPH Asia'26, NeurIPS'26
- Journal Reviewer: 
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (TPAMI)
  - Pattern Recognition
  - Transactions on Machine Learning Research (TMLR)
  - Expert Systems With Applications

# ✏️ Teaching Assistant
- [EE531] Statistical Learning Theory: 2025 Spring, 2026 Spring
- [EE331] Introduction to Machine Learning: 2024 Fall

<!-- # 💬 Invited Talks
- *2021.06*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet. 
- *2021.03*, Lorem ipsum dolor sit amet, consectetur adipiscing elit. Vivamus ornare aliquet ipsum, ac tempus justo dapibus sit amet.  \| [\[video\]](https://github.com/)

# 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->