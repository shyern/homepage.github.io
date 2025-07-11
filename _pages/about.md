---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  h1 { font-size: 28px !important; }
  h2 { font-size: 24px !important; }
  h3 { font-size: 20px !important; }
  p, li { font-size: 18px !important; }
  .paper-box-text { font-size: 14px !important; }
</style>

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am a Ph.D. candidate in Institute of Artificial Intelligence and Robotics at [Xi’an Jiaotong University](http://www.aiar.xjtu.edu.cn/), advised by Prof. [Le Wang](https://scholar.google.com/citations?user=RypRCUQAAAAJ&hl=en&oi=ao).  I was also very glad to have the opportunity to be advised by Prof. [Sanping Zhou](https://scholar.google.com/citations?user=2Drvv44AAAAJ&hl=en). 
From November 2023 to November 2024, I joined the [University of Illinois Chicago (UIC)](https://www.uic.edu/) as a visiting scholar, advised by Prof. [Wei Tang](https://www.cs.uic.edu/~tangw/), working on collaborative research in video understanding and anomaly detection. Previously, I obtained my bachelor’s degree from Northwest A&F University in 2019.

🔭 My research interests include **video anomaly detection, traffic scene understanding, and multimodal learning, image generation**.

📨 I welcome any discussion, collaboration, or academic exchange.

<!-- 💻 I am currently seeking a faculty or postdoctoral position to further advance my research. If you are aware of any relevant opportunities, I would be very grateful if you could let me know. -->



# 🔥 News
- *2024.07*：&nbsp;🎉🎉 One [paper](https://link.springer.com/chapter/10.1007/978-3-031-72658-3_10) on unsupervised video anomaly detection got accepted by ECCV 2024.
- *2023.11*：&nbsp;🎉🎉 One [paper](https://ieeexplore.ieee.org/document/10330089) on weakly-supervised video anomaly detection got accepted by IEEE Transactions on Multimedia (TMM).
- *2023.01*：&nbsp;🎉🎉 One paper [(MAAM-Net)](https://www.sciencedirect.com/science/article/pii/S0031320323000365) on one-class video anomaly detection got accepted by Pattern Recognition (PR).
- *2021.09*：&nbsp;🎉🎉 One [paper](https://www.sciencedirect.com/science/article/pii/S0031320321005318) on person image generation got accepted by Pattern Recognition (PR).
- *2020.08*：&nbsp;🎉🎉 One [paper](https://www.bmvc2020-conference.com/assets/papers/0406.pdf) on person image generation got accepted by BMVC 2020.

# 📝 Publications 
<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/papers/learning2024.png" alt="sym" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Learning Anomalies with Normality Prior for Unsupervised Video Anomaly Detection</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Haoyue Shi</u></strong>, Le Wang, Sanping Zhou, Gang Hua, and Wei Tang</p>
    <p style="margin: 0 0 10px 0;">ECCV 2024</p>
    <p style="margin: 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-031-72658-3_10">Paper</a> |
      <a href="https://github.com/shyern/LANP-UVAD">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/papers/abnormal2023.png" alt="sym" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Abnormal Ratios Guided Multi-Phase Self-Training for Weakly-Supervised Video Anomaly Detection</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Haoyue Shi</u></strong>, Le Wang, Sanping Zhou, Gang Hua, and Wei Tang</p>
    <p style="margin: 0 0 10px 0;">IEEE Transactions on Multimedia 2023</p>
    <p style="margin: 0;">
      <a href="https://ieeexplore.ieee.org/document/10330089">Paper</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/papers/memory2023.png" alt="sym" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Memory-augmented appearance-motion network for video anomaly detection</h3>
    <p style="margin: 0 0 10px 0;">Le Wang, Junwen Tian, Sanping Zhou, <strong><u>Haoyue Shi</u></strong>, Gang Hua, and Wei Tang</p>
    <p style="margin: 0 0 10px 0;">Pattern Recognition 2023</p>
    <p style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0031320323000365">Paper</a> |
      <a href="https://github.com/Owen-Tian/MAAM-Net">Code</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/papers/loss2021.png" alt="sym" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Loss functions for pose guided person image generation</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Haoyue Shi</u></strong>, Le Wang, Nanning Zheng, Gang Hua, and Wei Tang</p>
    <p style="margin: 0 0 10px 0;">Pattern Recognition 2021</p>
    <p style="margin: 0;">
      <a href="https://www.sciencedirect.com/science/article/pii/S0031320321005318">Paper</a>
      </p>
  </div>
</div>

<hr />

<div style="display: flex; align-items: center; margin-top: 30px; margin-bottom: 30px;">
  <img src="images/papers/loss2020.png" alt="sym" style="width: 200px; height: 100px; margin-right: 20px;">
  <div style="line-height: 1.2;">
    <h3 style="margin: 0 0 10px 0; font-weight: bold;">Loss Functions for Person Image Generation</h3>
    <p style="margin: 0 0 10px 0;"><strong><u>Haoyue Shi</u></strong>, Le Wang, Wei Tang, Nanning Zheng, and Gang Hua </p>
    <p style="margin: 0 0 10px 0;">BMVC 2020</p>
    <p style="margin: 0;">
      <a href="https://www.bmvc2020-conference.com/assets/papers/0406.pdf">Paper</a>
      </p>
  </div>
</div>

# 🎖 Honors and Awards
- Outstanding Graduate Student (Xi'an Jiaotong University), 2024. 
- China Mobile Scholarship (Xi’an Jiaotong University), 2024.
- Special Scholarship for Doctoral Students (Xi’an Jiaotong University), 2023
- Baosheng Hu Scholarship (Xi’an Jiaotong University), 2021
- Outstanding Undergraduate Thesis Award (Northwest A&F University), 2019
- Third Prize, The 3rd China Data Mining Competition, 2018
- President’s Scholarship (Northwest A&F University), 2018
- National Endeavor Scholarship (Northwest A&F University), 2016 & 2017

<!-- # 📖 Educations
- *2019.09 - 2025.07 (now)*, Xi’an Jiaotong University, Ph.D. in Control Science and Engineering
- *2023.11 – 2024.11*, University of Illinois Chicago, Visiting Scholar in Computer Science
- *2015.09 – 2019.07*, Northwest A&F University, B.E. in Software Engineering -->

# 📖 Professional services
## Conference Reviewer
* CVPR, ICCV, ECCV

## Journal Reviewer
* PR, TMM, MVAP, SIVP

# 💬 Posters
- *2024.10*, European Conferenceon Computer Vision, Milan, Italy
- *2024.09*, Midwest Computer Vision Workshop, Indiana University, USA

<!-- # 💻 Internships
- *2019.05 - 2020.02*, [Lorem](https://github.com/), China. -->

<div style="display: flex; justify-content: center; align-items: center; height: 200px;">
  <script type="text/javascript" id="clstr_globe" src="//clustrmaps.com/globe.js?d=1pTG0F_YNqjOwWHVuzu9bdtg51FIdqFqyj-hriK-W2E&w=150&h=150&t=light&cmo=#FF5588&cmn=#88FF55"></script>
</div>