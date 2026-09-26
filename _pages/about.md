---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<span class="anchor" id="about-me"></span>

<p class="lede">Junning Qiu is at <a href="https://en.engineai.com.cn/">众擎 (Engine AI)</a>. The work is grouped into three parts: embodied foundation models, embodied manipulation, and embodied perception.</p>

<div class="focus-row" markdown="0">
  <span class="focus-chip primary">具身基座模型</span>
  <span class="focus-chip primary">具身操作</span>
  <span class="focus-chip primary">具身感知</span>
</div>

<span class="anchor" id="foundation"></span>

# 具身基座模型

<p class="section-en">Embodied foundation models · 众擎, 2025.07 – present</p>

<p class="work-note">Native 2D/3D spatial representations and large-scale multimodal models for robotics, including <a href="https://arxiv.org/abs/2609.02359">TempoGround</a> and vision-language-action architectures. The same line builds a data-to-model closed loop that turns real robot interaction into the next round of model training.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="venue-tile arxiv">arXiv<span>2026</span></div></div></div>
-->
<div class="paper-box-text" markdown="1">

<span class="venue-label">arXiv 2026</span>

[TempoGround: State-Aware Streaming Visual Grounding with Vision-Language Models](https://arxiv.org/abs/2609.02359)

Leqian Ding, **Junning Qiu**<sup>✉</sup>, Manwen Yang, Yu Guo<sup>✉</sup>, Fei Wang

The VLM pretraining paper. TempoGround is trained from Qwen3.5 in three stages: ~26M single-frame samples for 2D detection and camera-frame 3D lifting, ~5.1M streaming samples for cross-frame correspondence and presence, followed by reinforcement learning with grounding, identity, and consistency rewards. At each streaming frame, it tracks object identity, determines temporal presence (enter, stay, or leave), and lifts 2D bounding boxes directly into the camera frame.

<div class="paper-links" markdown="0">
<a href="https://arxiv.org/abs/2609.02359">arXiv</a>
<a href="https://arxiv.org/pdf/2609.02359">PDF</a>
</div>

</div>
</div>

<span class="anchor" id="manipulation"></span>

# 具身操作

<p class="section-en">Embodied manipulation · 众擎, 2025.07 – present</p>

<p class="work-note">Manipulation deployment on the T800 humanoid, including RL-based whole-body control. Earlier work estimates 7-DoF grasp poses in clutter.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="venue-tile icra">ICRA<span>2026</span></div></div></div>
-->
<div class="paper-box-text" markdown="1">

<span class="venue-label">ICRA 2026</span>

EdgeGrasp: Enhancing Edge Perception for 7-DoF Grasping Pose Estimation in Cluttered Scenes

**Junning Qiu**, Fei Wang, Yu Guo, Yonggen Ling, Minglei Lu

7-DoF grasp pose estimation in clutter, with estimation driven by enhanced geometric edge cues.

</div>
</div>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="badge">IROS 2023</div><img src="images/IROS2023.png" alt="Teaser for voxel-based 7-DoF grasping"></div></div>
-->
<div class="paper-box-text" markdown="1">

<span class="venue-label">IROS 2023</span>

Multi-Source Fusion for Voxel-Based 7-DoF Grasping Pose Estimation

**Junning Qiu**, Fei Wang, Zheng Dang

Voxel-based 7-DoF grasping using positional encoding, 2D convolution, and gated cross-modal fusion to prevent loss of boundary and pose details within discretized grids.

<div class="paper-links" markdown="0">
<a href="https://youtu.be/fYIzs0q1Des">Video</a>
</div>

</div>
</div>

<span class="anchor" id="perception"></span>

# 具身感知

<p class="section-en">Embodied perception · 众擎, 2025.07 – present</p>

<p class="work-note">Autonomous perception and tracking on the T800. Earlier work covers stereo category-level shape and 6D pose, and the gap between learned 3D registration and real scans.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="badge">CVPR 2025</div><img src="images/CVPR2025.jpg" alt="Teaser for stereo category-level shape and 6D pose estimation"></div></div>
-->
<div class="paper-box-text" markdown="1">

<span class="venue-label">CVPR 2025</span>

[Leveraging Global Stereo Consistency for Category-Level Shape and 6D Pose Estimation from Stereo Images](https://openaccess.thecvf.com/content/CVPR2025/html/Qiu_Leveraging_Global_Stereo_Consistency_for_Category-Level_Shape_and_6D_Pose_CVPR_2025_paper.html)

**Junning Qiu**, Minglei Lu, Fei Wang, Yu Guo, Yonggen Ling

Category-level shape and 6D pose from a stereo pair. Global stereo consistency avoids degenerate solutions across shape, pose, and scale, maintaining accuracy even on challenging surfaces where active depth sensors degrade.

<div class="paper-links" markdown="0">
<a href="https://openaccess.thecvf.com/content/CVPR2025/html/Qiu_Leveraging_Global_Stereo_Consistency_for_Category-Level_Shape_and_6D_Pose_CVPR_2025_paper.html">Paper</a>
<a href="https://openaccess.thecvf.com/content/CVPR2025/papers/Qiu_Leveraging_Global_Stereo_Consistency_for_Category-Level_Shape_and_6D_Pose_CVPR_2025_paper.pdf">PDF</a>
<a href="https://openaccess.thecvf.com/content/CVPR2025/supplemental/Qiu_Leveraging_Global_Stereo_CVPR_2025_supplemental.zip">Supp.</a>
</div>

</div>
</div>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="venue-tile arxiv">arXiv<span>2021</span></div></div></div>
-->
<div class="paper-box-text" markdown="1">

<span class="venue-label">arXiv 2021</span>

[What Stops Learning-based 3D Registration from Working in the Real World?](https://arxiv.org/abs/2111.10399)

Zheng Dang, Lizhou Wang, **Junning Qiu**, Minglei Lu, Mathieu Salzmann

Systematic investigation into failure modes of point-cloud registration networks on real sensor data, with architectural and training prescriptions for zero-shot synthetic-to-real generalization.

<div class="paper-links" markdown="0">
<a href="https://arxiv.org/abs/2111.10399">arXiv</a>
</div>

</div>
</div>

<span class="anchor" id="news"></span>

# News

- *2026.09*: [TempoGround](https://arxiv.org/abs/2609.02359) is on arXiv. Pretraining state-aware streaming visual grounding VLMs for robotics. Corresponding author.
- *2026*: EdgeGrasp accepted to ICRA 2026.
- *2025.07*: Joined 众擎 (Engine AI). Work covers embodied foundation models, manipulation, and perception on the T800.
- *2025.02*: One paper accepted to CVPR 2025 on category-level shape and 6D pose estimation.

<span class="anchor" id="openings"></span>

# Openings

<div class="opening" markdown="1">

Open research and engineering positions on a rolling basis, focusing on:

- **Vision-Language Foundation Model Pretraining**: Native 2D/3D spatial representations, streaming multi-frame reasoning, multimodal alignment, and large-scale post-training (RLHF/RLAIF) for embodied perception.
- **Data-to-Model Closed Loop**: Scalable data curation, automated synthesis, high-throughput auto-labeling, and closed-loop data engine infrastructure for continuous foundation model iteration.

长期招募研究员与算法工程师（校招 / 社招 / 研究实习均可，滚动招聘），核心聚焦方向：

- **VLM 基座模型预训练**：多模态表征学习、原生 2D/3D 空间理解、流式视频推理、长上下文理解与对齐微调 / 强化学习。
- **数据到模型的全链路闭环**：大规模高质量多模态数据挖掘、自动化标注与合成生成体系、持续学习与基座模型迭代的数据飞轮建设。

欢迎对前沿视觉语言大模型预训练与数据自闭环体系有探索热情的朋友交流合作，请将简历直接发送至 <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>。

</div>

<span class="anchor" id="education"></span>

# Education

- M.S., Xi'an Jiaotong University.
- B.S., Northwestern Polytechnical University.

National Scholarship. Xi'an Jiaotong University Special Scholarship. First prizes and leadership in national innovation competitions.
