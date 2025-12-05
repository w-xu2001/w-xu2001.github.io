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

I am **Xu Wang**, currently a Master's student in Computer Science and Technology at the College of Information Science and Engineering, **Hunan University** (Sept. 2023 - Present), supervised by **Prof. Ruihui Li** (Overseas Excellent Youth). Previously, I received my Bachelor's degree in Data Science and Big Data Technology from the School of Artificial Intelligence, **Guilin University of Electronic Technology** in June 2023.

I am cheerful, enthusiastic, sincere, rigorous, and down-to-earth. I am passionate about scientific research, actively participate in research projects, and keep a close eye on the latest developments in the field.

My research interests focus on:
- 3D Gaussian Splatting (3DGS)
- SLAM (Simultaneous Localization and Mapping)
- 3D Reconstruction
- Computer Vision & Graphics

<span class='anchor' id='-xl'></span>

# 🎓 Education
- *Sept. 2023 - Present*, **Hunan University**, Changsha, Hunan, Master (Computer Science and Technology)
- *Sept. 2019 - June 2023*, **Guilin University of Electronic Technology**, Guilin, Guangxi, Bachelor (Data Science and Big Data Technology)

<span class='anchor' id='-lwzl'></span>

# 📝 Publications

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">Sensors 2022</div><img src='images/sensors2022.svg' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

-	`Jian Tang`, Rongbiao Wang, Gongzhe Qiu, Yu Hu, Yihua Kang. Mechanism of magnetic flux leakage detection method based on the slotted ferromagnetic lift-off layer. *Sensors*, 2022, 22(9): 3587. (JCR:Q2; IF:3.847)  
[[网页]](https://dx.doi.org/10.3390/s22093587) [[预览]](https://github.com/tangjyan/tangjyan.github.io/blob/main/pdf/TangJ-2022-Mechanism%20of%20Magnetic%20Flux%20Leakage%20Detection%20Method%20Based%20on%20the%20Slotted.pdf) [[下载]](/pdf/TangJ-2022-Mechanism%20of%20Magnetic%20Flux%20Leakage%20Detection%20Method%20Based%20on%20the%20Slotted.pdf)

</div>
</div>

<div class='paper-box'><div class='paper-box-text' markdown="1">

- **Xu Wang**, Ying Liu, Xiaojun Chen, Jialin Wu, Xiaohao Zhang, Ruihui Li. MGS-SLAM: Dense RGB-D SLAM via Multi-level Gaussian Splatting. *Pacific Graphics 2024 (PG 2024)*. (CCF-B)

- **Xu Wang**, Boyao Han, Ruihui Li, Qin Yunchuan, Jiapeng Zhang, Zhuo Tang, Kenli Li. PointSLAM++: Robust Dense Neural Gaussian Point Cloud-based SLAM. *The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)*. (Under Review)

- Jialin Wu, Ying Liu, **Xu Wang**, Xiaohao Zhang, Zhuo Tang, Ruihui Li. TD-GS: Few-shot Object View Synthesis via Task-Disentangled 3D Gaussian Splatting. *2025 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2025)*. (CCF-B)

- Xiaohao Zhang, Xiaolin He, Jialin Wu, **Xu Wang**, Zhuo Tang, Ruihui Li. High-Fidelity Single-View Reconstruction of Indoor Scenes using 3D Shape Prior Template and Pixel-Aligned Deformation. *2025 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2025)*. (CCF-B)

</div></div>

<span class='anchor' id='-kyjl'></span>

# 🔬 Research Experience

### Research on RGB-D SLAM System Based on 3D Gaussian Splatting (3DGS)
*Research Topic*
This project mainly studies the construction of an RGB-D SLAM system based on 3D Gaussian Splatting technology, innovating neural Gaussian representation, splatting rendering, and pose optimization methods to achieve scene structural consistency, robust localization, and high-fidelity 3D reconstruction rendering. Main work includes:
- Combined hierarchical constrained neural Gaussian representation with multi-level Gaussian Splatting initialization to achieve structural consistency and detailed hierarchical reconstruction, reducing geometric error by 22.3% and improving reconstruction quality by 12.36% compared to other methods.
- Proposed progressive pose optimization and dynamic Gaussian node distribution strategies, effectively suppressing depth noise and adapting to geometric complexity, increasing tracking speed by 25 times and mapping speed by 5 times compared to other methods.

### "Crossing Obstacles 2023" Land Unmanned System
*Project Member*
Integrated the autonomous maneuvering environmental perception and modeling software system into the test system, received offline test data (off-road environment data collection and calibration), and completed intelligent algorithm tests such as passable area environmental perception and modeling, and maneuvering obstacle recognition. Main work includes:
- Completed real-time high-precision odometry and environmental mapping based on the ROS framework and Faster-LIO algorithm.
- Tightly coupled GPS data with IMU filtering to achieve a global positioning error of less than 1 meter.

### National Natural Science Foundation Projects
Participated in the supervisor's National Natural Science Foundation Major Project and General Project, assisting in writing project proposals, etc.

<span class='anchor' id='-ryjx'></span>

# 🏅 Honors and Awards
- National Scholarship for Graduate Students
- Autonomous Region Government Scholarship (2 times)
- Undergraduate First Class Scholarship (3 times)
- First Prize, "Higher Education Press Cup" National Undergraduate Mathematical Contest in Modeling
- First Prize, China Engineering Robot Competition and International Open
- Second Prize, China Robot & Artificial Intelligence Competition
- Second Prize, Graduate Computer Innovation Competition
- Third Prize, "Huawei Challenge" Gaussian Reconstruction Competition

<span class='anchor' id='-gzsx'></span>

# 💻 Campus Experience
- Class League Secretary
- Student Union Member
- Graduate Teaching Assistant
