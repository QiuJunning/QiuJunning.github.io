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

I am a PhD candidate at the School of Artificial Intelligence, Xi'an Jiaotong University. My research interests are computer vision, 6D pose estimation, and robot manipulation.

# 🔥 News
- *2023.06*: &nbsp;🎉🎉 1 paper accepted to IROS2023.


# 📝 Publications 
Corresponding author$^\dagger$

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2023</div><img src='images/IROS2023.png' alt="sym" width="100%"></div></div>
<div class='paper-box-text' markdown="1">

Multi-Source Fusion for Voxel-Based 7-DoF Grasping Pose Estimation, IEEE/RSJ International Conference on Intelligent Robots and Systems(IROS)2023

Check out the [video demo here](https://youtu.be/fYIzs0q1Des) for a detailed look!

**Junning Qiu**, Fei Wang, Zheng Dang$^\dagger$

Abstract: In this work, we tackle the problem of estimating the grasping pose of a parallel-jaw gripper from point cloud data, which is a fundamental task in robotic manipulation. Most existing methods adopt 3D voxel CNNs as the backbone for their efficiency in handling unordered point cloud data. However, we found that these approaches overlook details information of the point clouds, resulting in decreased performance.Through our analysis, we identified quantization loss and boundary information loss within 3D convolutional layers as the two primary reasons for limitations of voxelization in 7-DoF grasping pose estimation.
To address these challenges, we introduced two novel branches: positional encoding branch and 2D convolution branch and a novel multi-source fusion gated mechanism.
Our approach achieved state-of-the-art performance on the Graspnet-1Billion benchmark and demonstrated high success rates in real robotic experiments across different scenes.
</div>
</div>

# 🎖 Honors and Awards
- National Scholarship. 
- Xi'an Jiaotong University Special Scholarship.

# 📖 Educations
- *2021.09 - Now*, Xi'an Jiaotong University. 
- *2017.09 - 2021.06*, Northwestern Polytechnical University. 

# PrePrint
[What Stops Learning-based 3D Registration from Working in the Real World?](https://arxiv.org/abs/2111.10399)

Zheng Dang, Lizhou Wang, **Junning Qiu**, Minglei Lu, Mathieu Salzmann
