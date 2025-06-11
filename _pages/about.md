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

I received a Master of Science (M.S.) from Xi'an Jiaotong University and am currently a full-time research intern at Tencent Robotics X. My research experience spans a range of topics in computer vision and robotics, including 3D reconstruction with RGBD and stereo sensors, 6D pose estimation, 7-DoF grasp pose estimation, and robot system setup and calibration. I am broadly interested in embodied intelligence, with a particular focus on robotic perception and VLA (Vision-Language-Action).  
**I am actively seeking Ph.D. positions in computer vision or robotics for Spring or Fall 2026. Please feel free to contact me at junning.qiu@stu.xjtu.edu.cn.**


# 🔥 News
- *2025.02*: &nbsp;🎉🎉 1 paper accepted to CVPR2025.
- *2023.06*: &nbsp;🎉🎉 1 paper accepted to IROS2023.


# 📝 Publications 
<div class='paper-box'><div class='paper-box-image'><div><div class="badge">CVPR 2025</div><img src='images/CVPR2025.jpg' alt="sym" style="height: 180px; object-fit: cover; width: 100%;">
</div></div>
<div class='paper-box-text' markdown="1">

Leveraging Global Stereo Consistency for Category-Level Shape and 6D Pose Estimation from Stereo Images (CVPR2025)

Download the [video demo here]([https://your-demo-link.com](https://openaccess.thecvf.com/content/CVPR2025/supplemental/Qiu_Leveraging_Global_Stereo_CVPR_2025_supplemental.zip)) for a detailed look!

**Junning Qiu**, Minglei Lu, Fei Wang, Yu Guo, Yonggen Ling

A stereo-based method is proposed to mitigate inherent parameter entanglement in category-level shape and 6D pose estimation by leveraging global stereo consistency, enabling robust performance across diverse materials without relying on explicit depth.

</div>
</div>

<div class='paper-box'><div class='paper-box-image'><div><div class="badge">IROS 2023</div><img src='images/IROS2023.png' alt="sym" style="height: 180px; object-fit: cover; width: 100%;">
</div></div>
<div class='paper-box-text' markdown="1">

Multi-Source Fusion for Voxel-Based 7-DoF Grasping Pose Estimation (IROS2023)

Check out the [video demo here](https://youtu.be/fYIzs0q1Des) for a detailed look!

**Junning Qiu**, Fei Wang, Zheng Dang

Addresses quantization loss and boundary information loss in voxel-based 7-DoF grasping via positional encoding, 2D convolution, and a gated fusion mechanism.
</div>
</div>

# 🎖 Honors and Awards
- National Scholarship.
- Team Leader of Multiple Award-Winning Projects in National Innovation and Entrepreneurship Competitions.
- Xi'an Jiaotong University Special Scholarship.

# 📖 Educations
- *2021.09 - 2025.06*, Xi'an Jiaotong University. 
- *2017.09 - 2021.06*, Northwestern Polytechnical University. 

# PrePrint
[What Stops Learning-based 3D Registration from Working in the Real World?](https://arxiv.org/abs/2111.10399)

Zheng Dang, Lizhou Wang, **Junning Qiu**, Minglei Lu, Mathieu Salzmann
