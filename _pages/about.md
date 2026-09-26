---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<div class="home" markdown="0">

<span class="anchor" id="about-me"></span>

<p class="lede">Junning Qiu works on embodied intelligence at <a href="https://en.engineai.com.cn/">Engine AI</a>. Since 2025 the work has covered foundation models, manipulation, and perception.</p>

<div class="focus-row">
  <a class="focus-chip primary" href="#foundation">Foundation models</a>
  <a class="focus-chip primary" href="#manipulation">Manipulation</a>
  <a class="focus-chip primary" href="#perception">Perception</a>
</div>

<span class="anchor" id="foundation"></span>

<h1>Embodied Foundation Models</h1>

<p class="work-note">Vision-language pretraining here is aimed at model paradigms and training methods with native embodied ability: native 2D/3D perception, and objectives tied to robot tasks. Real robot interaction is fed back into the next round of training. <a href="https://arxiv.org/abs/2609.02359">TempoGround</a> is the pretraining paper.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="venue-tile arxiv">arXiv<span>2026</span></div></div></div>
-->
<div class="paper-box-text">
<span class="venue-label">arXiv 2026</span>
<a class="paper-title" href="https://arxiv.org/abs/2609.02359">TempoGround: State-Aware Streaming Visual Grounding with Vision-Language Models</a>
<p class="paper-authors">Leqian Ding, <strong>Junning Qiu</strong><sup>✉</sup>, Manwen Yang, Yu Guo<sup>✉</sup>, Fei Wang</p>
<p class="paper-summary">Pretrains a vision-language model, from Qwen3.5, for streaming grounding: native 2D detection and camera-frame 3D lifting, then cross-frame identity and presence.</p>
<div class="paper-links">
<a href="https://arxiv.org/abs/2609.02359">arXiv</a>
<a href="https://arxiv.org/pdf/2609.02359">PDF</a>
</div>
</div>
</div>

<span class="anchor" id="manipulation"></span>

<h1>Embodied Manipulation</h1>

<p class="work-note">Autonomous manipulation on the T800 humanoid, including reinforcement-learning whole-body control. Earlier work estimates 7-DoF grasps in clutter.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="venue-tile icra">ICRA<span>2026</span></div></div></div>
-->
<div class="paper-box-text">
<span class="venue-label">ICRA 2026</span>
<p class="paper-title">EdgeGrasp: Enhancing Edge Perception for 7-DoF Grasping Pose Estimation in Cluttered Scenes</p>
<p class="paper-authors"><strong>Junning Qiu</strong>, Fei Wang, Yu Guo, Yonggen Ling, Minglei Lu</p>
<p class="paper-summary">7-DoF grasp poses in clutter, driven by stronger geometric edge cues.</p>
</div>
</div>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="badge">IROS 2023</div><img src="images/IROS2023.png" alt="Teaser for voxel-based 7-DoF grasping"></div></div>
-->
<div class="paper-box-text">
<span class="venue-label">IROS 2023</span>
<p class="paper-title">Multi-Source Fusion for Voxel-Based 7-DoF Grasping Pose Estimation</p>
<p class="paper-authors"><strong>Junning Qiu</strong>, Fei Wang, Zheng Dang</p>
<p class="paper-summary">Voxel-based 7-DoF grasping that keeps boundary and pose detail.</p>
<div class="paper-links">
<a href="https://youtu.be/fYIzs0q1Des">Video</a>
</div>
</div>
</div>

<span class="anchor" id="perception"></span>

<h1>Embodied Perception</h1>

<p class="work-note">Autonomous perception and tracking on the T800. Earlier work estimates category-level shape and 6D pose from stereo, and studies why learned 3D registration fails on real scans.</p>

<div class="paper-box">
<!-- image held out for now
<div class="paper-box-image"><div class="paper-thumb"><div class="badge">CVPR 2025</div><img src="images/CVPR2025.jpg" alt="Teaser for stereo category-level shape and 6D pose estimation"></div></div>
-->
<div class="paper-box-text">
<span class="venue-label">CVPR 2025</span>
<a class="paper-title" href="https://openaccess.thecvf.com/content/CVPR2025/html/Qiu_Leveraging_Global_Stereo_Consistency_for_Category-Level_Shape_and_6D_Pose_CVPR_2025_paper.html">Leveraging Global Stereo Consistency for Category-Level Shape and 6D Pose Estimation from Stereo Images</a>
<p class="paper-authors"><strong>Junning Qiu</strong>, Minglei Lu, Fei Wang, Yu Guo, Yonggen Ling</p>
<p class="paper-summary">Category-level shape and 6D pose from stereo, including where depth sensors fail.</p>
<div class="paper-links">
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
<div class="paper-box-text">
<span class="venue-label">arXiv 2021</span>
<a class="paper-title" href="https://arxiv.org/abs/2111.10399">What Stops Learning-based 3D Registration from Working in the Real World?</a>
<p class="paper-authors">Zheng Dang, Lizhou Wang, <strong>Junning Qiu</strong>, Minglei Lu, Mathieu Salzmann</p>
<p class="paper-summary">Why learned point-cloud registration fails on real scans, and what lets a synthetic-trained model transfer.</p>
<div class="paper-links">
<a href="https://arxiv.org/abs/2111.10399">arXiv</a>
</div>
</div>
</div>

<span class="anchor" id="news"></span>

<h1>News</h1>

<ul class="news-list">
  <li><time>2026.09</time><span><a href="https://arxiv.org/abs/2609.02359">TempoGround</a> on arXiv. Corresponding author.</span></li>
  <li><time>2026</time><span>EdgeGrasp at ICRA 2026.</span></li>
  <li><time>2025.07</time><span>Joined Engine AI.</span></li>
  <li><time>2025.02</time><span>One paper at CVPR 2025.</span></li>
</ul>

<span class="anchor" id="openings"></span>

<h1>Openings</h1>

<div class="opening">
<p>Research and engineering roles are open on a rolling basis, including internships. The focus is vision-language pretraining for embodied models, and the data loop that trains them.</p>
<p>Email a resume to <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>.</p>
</div>

<span class="anchor" id="education"></span>

<h1>Education</h1>

<ul class="edu-list">
  <li>M.S., Xi'an Jiaotong University.</li>
  <li>B.S., Northwestern Polytechnical University.</li>
</ul>
<p class="honors">National Scholarship. Xi'an Jiaotong University Special Scholarship.</p>

</div>
