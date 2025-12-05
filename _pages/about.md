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

我是王旭（Xu Wang），目前是湖南大学信息科学与工程学院计算机科学与技术专业的硕士研究生（2023年9月至今），师从**李瑞辉教授**（海外优青）。此前，我于2023年6月在桂林电子科技大学人工智能学院获得数据科学与大数据技术学士学位。

我的性格开朗，热情真诚，做事严谨，脚踏实地。我热爱科研，积极参与科研项目，密切关注领域内的最新动态。

我的研究兴趣主要集中在：
- 3D Gaussian Splatting (3DGS)
- SLAM (Simultaneous Localization and Mapping)
- 3D Reconstruction
- Computer Vision & Graphics

<span class='anchor' id='-xl'></span>

# 🎓 学历
- *2023.09 - 至今*, 湖南大学, 湖南长沙, 硕士 (计算机科学与技术)
- *2019.09 - 2023.06*, 桂林电子科技大学, 广西桂林, 学士 (数据科学与大数据技术)

<span class='anchor' id='-lwzl'></span>

# 📝 论文成果

<div class='paper-box'><div class='paper-box-text' markdown="1">

- **Xu Wang**, Ying Liu, Xiaojun Chen, Jialin Wu, Xiaohao Zhang, Ruihui Li. MGS-SLAM: Dense RGB-D SLAM via Multi-level Gaussian Splatting. *Pacific Graphics 2024 (PG 2024)*. (CCF-B)

- **Xu Wang**, Boyao Han, Ruihui Li, Qin Yunchuan, Jiapeng Zhang, Zhuo Tang, Kenli Li. PointSLAM++: Robust Dense Neural Gaussian Point Cloud-based SLAM. *The Thirty-Ninth Annual Conference on Neural Information Processing Systems (NeurIPS 2025)*. (Under Review)

- Jialin Wu, Ying Liu, **Xu Wang**, Xiaohao Zhang, Zhuo Tang, Ruihui Li. TD-GS: Few-shot Object View Synthesis via Task-Disentangled 3D Gaussian Splatting. *2025 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2025)*. (CCF-B)

- Xiaohao Zhang, Xiaolin He, Jialin Wu, **Xu Wang**, Zhuo Tang, Ruihui Li. High-Fidelity Single-View Reconstruction of Indoor Scenes using 3D Shape Prior Template and Pixel-Aligned Deformation. *2025 IEEE International Conference on Acoustics, Speech, and Signal Processing (ICASSP 2025)*. (CCF-B)

</div></div>

<span class='anchor' id='-kyjl'></span>

# 🔬 科研经历

### 基于3D高斯喷溅（3DGS）的RGB-D SLAM系统研究
*研究课题*
该课题主要研究基于3D高斯喷溅技术的RGB-D SLAM系统构建，创新神经高斯表示、喷溅渲染与位姿优化方法，实现场景结构一致、鲁棒定位及高保真3D重建渲染。主要工作如下：
- 结合分层约束神经高斯表示与多级Gaussian Splatting初始化，实现结构一致与细节分层重建，与其他方法比几何误差降低22.3%、重建质量提升12.36%。
- 提出渐进式位姿优化与动态高斯节点分布策略，有效抑制深度噪声并自适应几何复杂度，与其他方法比追踪速度提升25倍、建图速度提升5倍。

### “跨越险阻2023”陆上无人系统
*项目成员*
将自主机动环境感知与建模软件系统接入测试系统，接收离线测试数据（越野环境数据采集并标定），完成通行区域环境感知与建模、机动障碍识别等智能算法测试。主要工作如下：
- 基于ROS框架与Faster-LIO算法完成实时高精度里程计与环境建图。
- 将GPS数据与IMU紧耦合滤波，实现全局定位误差小于1米。

### 国家自然科学基金项目
参与导师的国家自然科学基金重大项目，国家自然科学基金面上项目，协助撰写项目书申报等。

<span class='anchor' id='-ryjx'></span>

# 🏅 荣誉奖项
- 硕士研究生国家奖学金
- 自治区人民政府奖学金 (2次)
- 本科生一等奖学金 (3次)
- 高教社杯全国大学生数学建模竞赛 一等奖
- 中国工程机器人大赛暨国际公开赛 一等奖
- 中国机器人及人工智能大赛 二等奖
- 研究生计算机创新大赛 二等奖
- “华为挑战杯”高斯重建大赛 三等奖

<span class='anchor' id='-gzsx'></span>

# 💻 校内经历
- 班级团支书
- 学生会委员
- 研究生助教
