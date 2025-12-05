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

# 👴 About Me

I am currently a first-year Ph.D. student jointly trained by Fudan University and Shanghai AI Lab, supervised by [Jing Shao](https://amandajshao.github.io/). Before that, I got my Master's degree at University of Science and Technology of China (USTC) and my Bachelor's degree from Dalian Maritime University (DLMU). 

My research interest mainly includes **Computer Vision**, **Deep Learning**, **AI Agent**, **Reinforcement Learning**, **Generative Models**. [My CV](https://yjyddq.github.io/files/resume.pdf) 📄

**Email** 📧: <u>yangjingyi946@gmail.com</u> or <u>yangjingyi@mail.ustc.edu.cn</u> or <u>jingyiyang25@m.fudan.edu.cn</u>

**Wechat** 📱: wxid_fa6qu0x94mud22

😀 <span style="color:red;">Please feel free to contact me for communication and collaboration.</span>


<h1 id='news'>🔥 News</h1>
<style>
  .scrollable {
    max-height: 260px; /* 设置最大高度 */
    overflow-y: scroll; /* 设置垂直滚动条 */
  }
</style>

<div class="scrollable">
  <ul>
    <li><strong>2025.12.01</strong>: We release the codebase of DARE: dLLM Alignment and Reinforcement Executor, a framework that enables efficient fine-tuning, reinforcement learning and comprehensive evaluation of dLLMs (Project Leader).</li>  
    <li><strong>2025.09.28</strong>: We release the paper and code of Taming Masked Diffusion Language Models via Consistency Trajectory Reinforcement Learning with Fewer Decoding Step (First Author).</li>  
    <li><strong>2025.09.18</strong>: 1 paper was accepted to NeurIPS 2025 (First Author).</li>
    <li><strong>2025.06.26</strong>: 1 paper was accepted to IEEE TIFS (First Author).</li>
    <li><strong>2025.06.26</strong>: 1 paper was accepted to ICCV 2025 (First Author).</li>
    <li><strong>2025.01.22</strong>: 1 paper was accepted to ICLR 2025 (First Author).</li>
    <li><strong>2024.07.04</strong>: 1 paper was accepted to ECAI 2024 (First Author), selected as an Oral 🎉🎉🎉.</li>
  </ul>
</div>


<h1 id='research-topics'>📝 Research Topics</h1>

#### Masked Diffusion Large Language Model & Reinforcement Learning
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``Github``</span> [DARE: dLLM Alignment and Reinforcement Executor](https://github.com/yjyddq/DARE). **Jingyi Yang**, Yuxian Jiang, ..., Jing Shao<sup>†</sup>


- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ArXiv``</span> [Taming Masked Diffusion Language Models via Consistency Trajectory Reinforcement Learning with Fewer Decoding Step](https://arxiv.org/pdf/2509.23924). **Jingyi Yang**, Guanxu Chen, Xuhao Hu, Jing Shao<sup>†</sup>


#### Large Reasoning Model & Reinforcement Learning
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ArXiv``</span> [Conditional Advantage Estimation for Reinforcement Learning in Large Reasoning Models](https://arxiv.org/pdf/2509.23962). Guanxu Chen, Yafu Li, Yuxian Jiang, Chen Qian, Qihan Ren, **Jingyi Yang**, Yu Cheng, Dongrui Liu, Jing Shao<sup>†</sup>
<!-- <br>
<a href="https://github.com/biuboomc/CANON">Code</a> <img src="https://img.shields.io/github/stars/biuboomc/CANON"/>
<br> -->

#### Computer-Use Agent & Self-Evolving Agent
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``NeurIPS 2025``</span> [RiOSWorld: Benchmarking the Risk of Multimodal Computer-Use Agents](https://arxiv.org/pdf/2506.00618). **Jingyi Yang**<sup>*</sup> <sup>‡</sup>, Shuai Shao<sup>*</sup>, Dongrui Liu, Jing Shao<sup>†</sup>


- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ArXiv``</span> [Your Agent May Misevolve: Emergent Risks in Self-evolving LLM Agents](https://arxiv.org/pdf/2509.26354). Shuai Shao, Qihan Ren, Chen Qian, Boyi Wei, Dadi Guo, **Jingyi Yang**, Xinhao Song, Linfeng Zhang, Weinan Zhang, Dongrui Liu, Jing Shao<sup>†</sup>
<!-- <br>
<a href="https://github.com/ShaoShuai0605/Misevolution">Code</a> <img src="https://img.shields.io/github/stars/ShaoShuai0605/Misevolution"/>
<br> -->

#### Video Understanding
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICLR 2025``</span> [Kronecker Mask and Interpretive Prompts are Language-Action Video Learners](https://arxiv.org/pdf/2502.03549). **Jingyi Yang**<sup>*</sup>, Zitong Yu<sup>*</sup>, Xiuming Ni, Jia He, Hui Li<sup>†</sup>


- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``IEEE TIFS``</span> [G<sup>2</sup>V<sup>2</sup>former: Graph Guided Video Vision Transformer for Face Anti-Spoofing](https://arxiv.org/abs/2408.07675). **Jingyi Yang**, Zitong Yu<sup>†</sup>, Jia He, Xiuming Ni, Liepiao Zhang, Hui Li<sup>†</sup>, Xiaochun Cao

#### Multi-Modal Learning & Domain Generalization for Face Anti-spoofing
- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ICCV 2025``</span> [DADM: Dual Alignment of Domain Modality for Face Anti-Spoofing](https://arxiv.org/pdf/2503.00429). **Jingyi Yang**<sup>*</sup>, Xun Lin<sup>*</sup>, Zitong Yu<sup>†</sup>, Liepiao Zhang, Xin Liu, Hui Li, Xiaochen Yuan, Xiaochun Cao


- <span style="background-color: #003366; color: white; padding: 1px 4px; font-size: 12px;">``ECAI 2024 Oral``</span> [Generalized Face Anti-spoofing via Finer Domain Partition and Disentangling Liveness-irrelevant Factors](https://arxiv.org/abs/2407.08243). **Jingyi Yang**, Zitong Yu, Xiuming Ni, Jia He, Hui Li<sup>†</sup>


<h1 id='selected-publications'>📖 Selected Publications (* Equal Contribution, ‡ Project Leader, † Corresponding Author)</h1>

<style>
  .tag {
    display: inline-block;
    background-color: #0073e6;
    color: rgb(33, 32, 32);
    padding: 3px 7px;
    border-radius: 15px;
    font-size: 0.8em;
    margin-right: 5px;
   }
  .tag-fas {
    background-color: #bde0fe;
  }
  .tag-mm {
    background-color: #ffc800;
  }
  .tag-video {
    background-color: #ffc8dd;
  }
  .tag-dllm {
    background-color: #cdb4db;
  }
  .tag-rl {
    background-color: #a2d2ff;
  }
  .tag-cua {
    background-color: #d8f060;
  }
</style>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ArXiv</div><img src='../images/EOSER_ASS_RL.jpg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Taming Masked Diffusion Language Models via Consistency Trajectory Reinforcement Learning with Fewer Decoding Step](https://arxiv.org/pdf/2509.23924)
<div class="tags" data-tags="dllm,rl"></div>
**Jingyi Yang**, Guanxu Chen, Xuhao Hu, Jing Shao<sup>†</sup>

<br>
<a href="https://github.com/yjyddq/EOSER-ASS-RL">**Code**</a> <img src="https://img.shields.io/github/stars/yjyddq/EOSER-ASS-RL?style=flat-square&logo=github&label=Stars"/> / 
<a href="https://mp.weixin.qq.com/s/O1e5zmkTPu8cNnCrMPUmTQ">**机器之心**</a> 
<br>

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">NeurIPS 2025</div><img src='../images/RiOSWorld.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[RiOSWorld: Benchmarking the Risk of Multimodal Computer-Use Agents](https://arxiv.org/pdf/2506.00618)
<div class="tags" data-tags="cua"></div>
**Jingyi Yang**<sup>*</sup> <sup>‡</sup>, Shuai Shao<sup>*</sup>, Dongrui Liu, Jing Shao<sup>†</sup>

<br>
<a href="https://yjyddq.github.io/RiOSWorld.github.io/">**Project HomePage**</a> /
<a href="https://github.com/yjyddq/RiOSWorld">**Code**</a> <img src="https://img.shields.io/github/stars/yjyddq/RiOSWorld?style=flat-square&logo=github&label=Stars"/> / 
<a href="https://huggingface.co/datasets/JY-Young/RiOSWorld">**Dataset**</a> <img src="https://img.shields.io/badge/🤗%20HuggingFace-Datasets-yellow"/> <a href="https://huggingface.co/api/datasets/JY-Young/RiOSWorld?expand=downloads&expand=downloadsAllTime">**Downloads**</a> /
<a href="https://mp.weixin.qq.com/s/YCg6FZG2Csz0W1fxvG3eMg">**机器之心**</a> 
<details>
  <summary>Demo</summary>
  <video controls width="100%">
    <source src="https://raw.githubusercontent.com/yjyddq/yjyddq.github.io/main/videos/RiOSWorld_demo.mp4" type="video/mp4">
  </video>
</details>
<br>

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICCV 2025</div><img src='../images/DADM.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[DADM: Dual Alignment of Domain Modality for Face Anti-Spoofing](https://arxiv.org/pdf/2503.00429)
<div class="tags" data-tags="fas,mm"></div>
**Jingyi Yang**<sup>*</sup>, Xun Lin<sup>*</sup>, Zitong Yu<sup>†</sup>, Liepiao Zhang, Xin Liu, Hui Li, Xiaochen Yuan, Xiaochun Cao

<br>
<a href="https://github.com/yjyddq/DADM">**Code**</a> <img src="https://img.shields.io/github/stars/yjyddq/DADM?style=flat-square&logo=github&label=Stars"/>
<br>

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ICLR 2025</div><img src='../images/CLAVER.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Kronecker Mask and Interpretive Prompts are Language-Action Video Learners](https://arxiv.org/pdf/2502.03549)
<div class="tags" data-tags="video,mm"></div>
**Jingyi Yang**<sup>*</sup>, Zitong Yu<sup>*</sup>, Xiuming Ni, Jia He, Hui Li<sup>†</sup>

<br>
<a href="https://github.com/yjyddq/CLAVER">**Code**</a>
<br>

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IEEE TIFS</div><img src='../images/GVformer.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[G<sup>2</sup>V<sup>2</sup>former: Graph Guided Video Vision Transformer for Face Anti-Spoofing](https://arxiv.org/abs/2408.07675)
<div class="tags" data-tags="fas,video,mm"></div>
**Jingyi Yang**, Zitong Yu<sup>†</sup>, Jia He, Xiuming Ni, Liepiao Zhang, Hui Li<sup>†</sup>, Xiaochun Cao

</div>
</div>

---

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">ECAI 2024 Oral 🎉</div><img src='../images/DLIF.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

[Generalized Face Anti-spoofing via Finer Domain Partition and Disentangling Liveness-irrelevant Factors](https://arxiv.org/abs/2407.08243)
<div class="tags" data-tags="fas"></div>
**Jingyi Yang**, Zitong Yu, Xiuming Ni, Jia He, Hui Li<sup>†</sup>

<br>
<a href="https://github.com/yjyddq/DLIF">**Code**</a>
<details>
  <summary>Demo</summary>
  <video controls width="100%">
    <source src="https://raw.githubusercontent.com/yjyddq/yjyddq.github.io/main/videos/fas.mp4" type="video/mp4">
  </video>
</details>
<br>

</div>
</div>


<h1 id='honors-and-awards'>🎖 Honors and Awards</h1>

- *2020, 2021, 2022* Excellent Student Scholarship - First Prize (2%) twice, Third Prize (10%) once
- *2022* Outstanding Graduates of Dalian City
- *2021* Competition Specific Scholarship
- *2021* The Mathematical Contest in Modeling (MCM)/Interdisciplinary Contest in Modeling (ICM) Honorable Mention
- *2019* The 11th National College Student Mathematics Competition Liaoning Province - Third Prize
- *2019* The 28th Dalian College Student Mathematics Competition - First Prize


<h1 id='academic-services'>💻 Academic Service</h1>

- Reviewer of IEEE International Joint Conference on Biometrics (IJCB) Multimodal Human Behavior Understanding & Generation 2024
- Reviewer of International Conference on Learning Representations 2025
- Reviewer of International Conference on Learning Representations 2026

<div style="width: 800px; height: 800px; margin: 0 auto; display: flex; justify-content: center; text-align: center;">
    <script type="text/javascript" id="clustrmaps" src="//clustrmaps.com/map_v2.js?d=etQgFBMwXmN9SCKnUHbRL9wr8n4MjpFP-KVHLoOB74o&cl=ffffff&w=a"></script>
</div>

<!-- Definations for tags -->
<script>
  // 预定义标签的名称和简称
  const tagsMap = {
    'fas': { name: 'Face Anti-Spoofing', class: 'tag-fas' },
    'video': { name: 'Video Understanding', class: 'tag-video' },
    'mm': { name: 'Multi-Modal Learning', class: 'tag-mm' },
    'dllm': { name: 'Diffusion Large Language Model', class: 'tag-dllm' },
    'rl': { name: 'Reinforcement Learning', class: 'tag-rl' },
    'cua': { name: 'Computer-Use Agent', class: 'tag-cua' },
  };

  // 渲染标签并为不同标签分配不同的CSS类
  document.querySelectorAll('.tags').forEach(tagDiv => {
    const tagAbbreviations = tagDiv.getAttribute('data-tags').split(',');
    tagAbbreviations.forEach(abbreviation => {
      if (tagsMap[abbreviation]) {
        const tagElement = document.createElement('span');
        tagElement.classList.add('tag', tagsMap[abbreviation].class);
        tagElement.textContent = tagsMap[abbreviation].name;
        tagDiv.appendChild(tagElement);
      }
    });
  });
</script>

