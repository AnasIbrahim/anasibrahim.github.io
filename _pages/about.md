---
permalink: /
title:
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

I am a PhD researcher at TU Dortmund University, nearing completion of my PhD in computer vision for robotics. My work focuses on deep learning methods for unseen objects, with a background in robotics hardware and software, including electronics, embedded systems, localization, and perception. My main research interests are generalized vision deep learning and high-speed perception with event cameras.



## Updates {#updates}

<ul class="small">
<li><strong>[August 2025]</strong> MR6D paper accepted at ICCV R6D Workshop</li>
<li><strong>[June 2025]</strong> BOP 2024 report presented at CVPR – CV4MR workshop</li>
<li><strong>[March 2025]</strong> MTevent paper accepted at CVPR – Event Vision workshop</li>
<li><strong>[October 2024]</strong> Our EventRec project on perception for high-speed robots officially started, following successful funding acquisition that I spearheaded</li>
<li><strong>[August 2024]</strong> "Centroid Triplet Loss" paper with University of Bonn presented at IEEE CASE 2024</li>
</ul>



## Publications {#publications}

<section class="publications">

<!-- MR6D -->
<div id="mr6d" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: 16:9 image box -->
  <div class="pub-thumb" style="position:relative; width:100%; aspect-ratio:16/9; background:#f9f9f9; border:1px solid #ddd; border-radius:6px; overflow:hidden; display:flex; align-items:center; justify-content:center;">
    <img src="/images_content/MR6D.png" alt="MR6D teaser image" loading="lazy"
         style="width:100%; height:100%; object-fit:contain;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2508.13775" target="_blank" rel="noopener">
        MR6D: Benchmarking 6D Pose Estimation for Mobile Robots
      </a>
    </h3>
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong><sup>1,3</sup>, Shrutarv Awasthi<sup>1</sup>,
      Christian Blesing<sup>2</sup>, Lokeshwaran Manohar<sup>1</sup>, 
      Frank Hoffmann<sup>1</sup>, Alice Kirchheim<sup>1,2,3</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> Fraunhofer IML · <sup>3</sup> Lamarr Institute
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      ICCV 2025 — R6D Workshop
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2508.13775" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://huggingface.co/datasets/anas-gouda/mr6d" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/hf-logo.png" alt="Hugging Face" style="height:16px;"> Dataset
      </a>
    </p>
  </div>
</div>

<!-- BOP Challenge 2024 -->
<div id="bop24" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/bop24.jpg" alt="BOP Challenge 2024 teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2504.02812" target="_blank" rel="noopener">
        BOP Challenge 2024 on Model-Based and Model-Free 6D Object Pose Estimation
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      Van Nguyen Nguyen<sup>1</sup>, Stephen Tyree<sup>2</sup>, Andrew Guo<sup>3</sup>,
      Médéric Fourmy<sup>4</sup>, <strong>Anas Gouda</strong><sup>5</sup>, Taeyeop Lee<sup>6</sup>
      Sungphill Moon<sup>7</sup>, Hyeontae Son<sup>7</sup>, Lukas Ranftl<sup>8,9</sup>,
      Jonathan Tremblay<sup>2</sup>, Eric Brachmann<sup>10</sup>, Bertram Drost<sup>8</sup>
      Vincent Lepetit<sup>1</sup>, Carsten Rother<sup>11</sup>, Stan Birchfield<sup>2</sup>,
      Jiri Matas<sup>4</sup>, Yann Labbé<sup>13</sup>, Martin Sundermeyer<sup>12</sup>,
      Tomas Hodan<sup>13</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      <sup>1</sup> ENPC ParisTech · <sup>2</sup> NVIDIA · <sup>3</sup> University of Toronto · 
      <sup>4</sup> CTU Prague · <sup>5</sup> TU Dortmund · <sup>6</sup> KAIST · <sup>7</sup> NAVER LABS · 
      <sup>8</sup> MVTec · <sup>9</sup> TU Munich · <sup>10</sup> Niantic · <sup>11</sup> Heidelberg University · 
      <sup>12</sup> Google · <sup>13</sup> Meta
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      CVPR 2025 – CV4MR Workshop
      <span style="color:#ff6666; font-weight:bold;">(Best Paper Award)</span>
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2504.02812" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
    </p>
  </div>
</div>

<!-- MTevent -->
<div id="mtevent" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: 2:3 image box -->
  <div class="pub-thumb" style="position:relative; width:100%; aspect-ratio:2/3; background:#f9f9f9; border:1px solid #ddd; border-radius:6px; overflow:hidden; display:flex; align-items:center; justify-content:center;">
    <img src="/images_content/MTevent_event_L_RGB.jpg" alt="MTevent teaser image" loading="lazy"
         style="width:100%; height:100%; object-fit:contain;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2504.02812" target="_blank" rel="noopener">
        MTevent: A Multi-Task Event Camera Dataset for 6D Pose Estimation and Moving Object Detection
      </a>
    </h3>
    <p class="pub-authors" style="margin:0.2em 0;">
      <span style="font-weight:600;">*</span>Shrutarv Awasthi<sup>1</sup>, 
      <strong>*Anas Gouda</strong><sup>1,2</sup>, 
      Sven Franke<sup>1</sup>, Jérôme Rutinowski<sup>1,2</sup>, 
      Frank Hoffmann<sup>1</sup>, Moritz Roidl<sup>1,2</sup>
    </p>
    <p class="pub-note" style="margin:0.2em 0; font-size:0.9em; opacity:0.85;">
      * Equal contribution.
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> Lamarr Institute
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      CVPR 2025 — Workshop on Event-based Vision
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2504.02812" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://openaccess.thecvf.com/content/CVPR2025W/EventVision/html/Awasthi_MTevent_A_Multi-Task_Event_Camera_Dataset_for_6D_Pose_Estimation_CVPRW_2025_paper.html" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         CVF
      </a>
      <a href="https://huggingface.co/datasets/anas-gouda/mtevent" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/hf-logo.png" alt="Hugging Face" style="height:16px;"> Dataset
      </a>
    </p>
  </div>
</div>

<!-- CTL -->
<div id="ctl" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: flexible height -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/CTL.png" alt="CTL teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2404.06277" target="_blank" rel="noopener">
        Learning Embeddings with Centroid Triplet Loss (CTL) for Object Identification in Robotic Grasping
      </a>
    </h3>
    <!-- Authors: 3 per line -->
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong><sup>1</sup>, Max Schwarz<sup>2</sup>, Christopher Reining<sup>1</sup>
      Sven Behnke<sup>2</sup>, Alice Kirchheim<sup>1,3</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> University of Bonn · <sup>3</sup> Fraunhofer IML
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      IEEE CASE 2024
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2404.06277" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10711720" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         IEEE
      </a>
      <a href="https://huggingface.co/spaces/anas-gouda/dounseen" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/hf-logo.png" alt="Hugging Face" style="height:16px;"> Space
      </a>
    </p>
  </div>
</div>

<!-- DoUnseen -->
<div id="dounseen" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/dounseen_paper.png" alt="DoUnseen teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2304.02833" target="_blank" rel="noopener">
        DoUnseen: Tuning-Free Class-Adaptive Object Detection of Unseen Objects for Robotic Grasping
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong>, Moritz Roidl
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      RSS 2023 – Workshop on Perception and Manipulation Challenges for Warehouse Automation (non-archival)
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2304.02833" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
    </p>
  </div>
</div>

<!-- Event Camera as Region Proposal Network -->
<div id="event_roi" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/Event_as_ROI.png" alt="Event Camera as RPN teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      Event Camera as Region Proposal Network
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      Shrutarv Awasthi, Richard Julian Lodenkaemper, <strong>Anas Gouda</strong>, Moritz Roidl
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      Preprint
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2305.00718" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
    </p>
  </div>
</div>

<!-- SensorFloor -->
<div id="sensorfloor" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/sensorfloor_render.jpg" alt="SensorFloor teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2212.04721" target="_blank" rel="noopener">
        SensorFloor: A Grid-based Sensor Floor Platform for Robot Localization using Machine Learning
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong>, Danny Heinrich, Mirco Hünnefeld, 
      Irfan Fachrudin Priyanta, Christopher Reining, Moritz Roidl
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      IEEE I2MTC 2023
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2212.04721" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10176013" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         IEEE
      </a>
    </p>
  </div>
</div>

<!-- The potential of deep learning in warehousing logistics -->
<div id="dl_in_log" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: empty white space -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <div style="width:100%; aspect-ratio:4/3; border:1px solid #fff; border-radius:6px; background:#fff;"></div>
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://proc.logistics-journal.de/article/view/1050" target="_blank" rel="noopener">
        The Potential of Deep Learning Based Computer Vision in Warehousing Logistics
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      Jérôme Rutinowski, Hazem Youssef, <strong>Anas Gouda</strong>, 
      Christopher Reining, Moritz Roidl
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      Logistics Journal: Proceedings, 2022
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://proc.logistics-journal.de/article/view/1050" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         Logistics Journal
      </a>
    </p>
  </div>
</div>

<!-- DoPose-6D -->
<div id="dopose" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/dopose.png" alt="DoPose-6D teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://arxiv.org/abs/2204.13613" target="_blank" rel="noopener">
        DoPose-6D: Dataset for Object Segmentation and 6D Pose Estimation
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong>, Ahmad Ghanem, Christopher Reining
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      ICMLA 2022
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://arxiv.org/abs/2204.13613" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         <img src="/images_content/arxiv-logo.png" alt="arXiv" style="height:16px;">
      </a>
      <a href="https://ieeexplore.ieee.org/abstract/document/10069586" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         IEEE
      </a>
      <a href="https://zenodo.org/records/6103779" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         Dataset
      </a>
    </p>
  </div>
</div>

<!-- Object Class-Agnostic Segmentation -->
<div id="agnostic_seg" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/iiwa_new.jpg" alt="Object Class-Agnostic Segmentation teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>

  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://ieeexplore.ieee.org/document/9680821" target="_blank" rel="noopener">
        Object Class-Agnostic Segmentation for Practical CNN Utilization in Industry
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      <strong>Anas Gouda</strong>, Abraham Ghanem, Pascal Kaiser, Michael ten Hompel
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      TU Dortmund
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      ICMERR 2021
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://ieeexplore.ieee.org/document/9680821" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         IEEE
      </a>
    </p>
  </div>
</div>

<!-- Decentralized Brains -->
<div id="debr" class="pub-item" style="display:grid; grid-template-columns:240px 1fr; gap:1rem; align-items:start; margin:1.5rem 0;">
  <!-- Left: thumbnail -->
  <div class="pub-thumb" style="width:100%; text-align:center;">
    <img src="/images_content/debr.jpg" alt="Decentralized Brains teaser image" loading="lazy"
         style="width:100%; height:auto; border:1px solid #ddd; border-radius:6px; background:#f9f9f9; padding:2px;">
  </div>
  <!-- Right: paper info -->
  <div class="pub-meta" style="line-height:1.35;">
    <h3 class="pub-title" style="margin:0 0 0.3em 0;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-71061-3_6" target="_blank" rel="noopener">
        Decentralized Brains: A Reference Implementation with Performance Evaluation
      </a>
    </h3>
    <!-- Authors -->
    <p class="pub-authors" style="margin:0.2em 0;">
      Aswin Venkatapathy<sup>1,2</sup>, <strong>Anas Gouda</strong><sup>1</sup>, 
      Michael ten Hompel<sup>1,2</sup>, Joseph Paradiso<sup>3</sup>
    </p>
    <p class="pub-affiliations" style="margin:0.2em 0; font-size:0.95em;">
      <sup>1</sup> TU Dortmund · <sup>2</sup> Fraunhofer IML · <sup>3</sup> MIT Media Lab
    </p>
    <p class="pub-venue" style="margin:0.3em 0; font-style:italic;">
      Industrial IoT 2020
    </p>
    <p class="pub-links" style="margin:0.6em 0; display:flex; flex-wrap:wrap; gap:0.6rem;">
      <a href="https://link.springer.com/chapter/10.1007/978-3-030-71061-3_6" target="_blank" rel="noopener"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; font-size:0.9em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem;">
         Springer
      </a>
    </p>
  </div>
</div>

</section>

## Projects {#projects}
<section class="projects">

<!-- Project: EventRec -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border:1px solid #ddd; border-radius:10px; background:#fafafa;">
  <h3 style="margin:0 0 0.5rem 0;">EventRec</h3>
  <p style="margin:0.25rem 0 1rem 0;">
    <a href="https://flw.mb.tu-dortmund.de/research/research-projects/eventrec" target="_blank" rel="noopener"
       style="display:inline-block; background:#e0e0e0; color:#000; padding:0.35em 0.9em; border-radius:0.4em; text-decoration:none; font-weight:600;">
      Project Page
    </a>
  </p>
  <div class="project-images" style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin:0 auto 1rem auto; max-width:1000px;">
  <img src="/images_content/eventrec_cam_system.jpg" alt="EventRec camera system"
       loading="lazy"
       style="height:180px; width:auto;">
  <img src="/images_content/EventRec.jpg" alt="EventRec O³dyn robot"
       loading="lazy"
       style="height:180px; width:auto;">
  </div>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">
      I proposed the EventRec project and led it from concept to securing funding from the AIF/IGF, in close collaboration with colleagues.
    </p>
    <p style="margin:0.4rem 0;">
      The project focuses on perception for high-speed robotics (e.g., the O³dyn robot) using event cameras.
      It develops generic methods with a multi-modal stereo-event and RGB camera system for 3D detection of
      fast-moving objects, enabling mobile robots to navigate at high speeds.
    </p>
    <p style="margin:0.4rem 0;">
      <strong>Industry partners:</strong> KION, Jungheinrich, Framos and others.
    </p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem;">
    <div style="margin:0.3rem 0;">
      <strong>Published Papers:</strong>
      <a href="{{ page.url | relative_url }}#mtevent"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">
         MTevent
      </a>
      <a href="{{ page.url | relative_url }}#event_roi"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">
         Event ROI
      </a>
    </div>
    <div style="margin:0.3rem 0; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Event Cameras</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">High-Speed Robotics</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">3D Detection</span>
    </div>
  </div>
</div>

<!-- Project: DoUnseen Package -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border:1px solid #ddd; border-radius:10px; background:#fafafa;">
  <h3 style="margin:0 0 0.5rem 0;">DoUnseen Package</h3>
  <p style="margin:0.25rem 0 1rem 0;">
    <a href="https://github.com/AnasIbrahim/image_agnostic_segmentation" target="_blank" rel="noopener"
       style="display:inline-block; background:#e0e0e0; color:#000; padding:0.35em 0.9em; border-radius:0.4em; text-decoration:none; font-weight:600;">
      Project Page
    </a>
  </p>
  <div class="project-images" style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin:0 auto 1rem auto; max-width:1000px;">
    <img src="/images_content/dounseen_logo_10.jpg" alt="DoUnseen logo"
         loading="lazy"
         style="height:180px; width:auto;">
  </div>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">Package for 2D segmentation of unseen objects and the main outcome of my PhD work.</p>
    <p style="margin:0.4rem 0;">The package segments arbitrary objects from only a few images, making it broadly applicable. I focused on two applications: bin picking and grasping for mobile robots, for which dedicated datasets were collected.</p>
    <p style="margin:0.4rem 0;">While the package itself targets segmentation, our centroid triplet loss (CTL) built on top of it achieved strong results on ArmBench. This line of work is especially relevant to logistics, where countless items must be segmented and classified, and parts have already been transferred to industry.</p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem;">
    <div style="margin:0.3rem 0;">
      <strong>Published Papers:</strong>
      <a href="{{ page.url | relative_url }}#ctl"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">CTL</a>
      <a href="{{ page.url | relative_url }}#dounseen"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">DoUnseen</a>
      <a href="{{ page.url | relative_url }}#dopose"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">DoPose</a>
      <a href="{{ page.url | relative_url }}#mr6d"
         style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">MR6D</a>
    </div>
    <div style="margin:0.3rem 0; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Unseen Object Segmentation</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Bin Picking</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Robotic Grasping</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Logistics</span>
    </div>
  </div>
</div>

<!-- Project: BOP Benchmark -->
<div class="project-item" style="text-align:center; margin:0.8rem 0; padding:1.5rem; border:1px solid #ddd; border-radius:10px; background:#fafafa;">
  <h3 style="margin:0 0 0.5rem 0;">BOP Benchmark</h3>
  <p style="margin:0.25rem 0 1rem 0;">
    <a href="https://bop.felk.cvut.cz/" target="_blank" rel="noopener" style="display:inline-block; background:#e0e0e0; color:#000; padding:0.35em 0.9em; border-radius:0.4em; text-decoration:none; font-weight:600;">Project Page</a>
  </p>
  <div class="project-images" style="display:flex; justify-content:center; gap:0.75rem; flex-wrap:wrap; margin:0 auto 1rem auto; max-width:1000px;">
    <img src="/images_content/BOP.jpg" alt="BOP Benchmark teaser" loading="lazy" style="height:180px; width:auto;">
  </div>
  <div class="project-desc" style="max-width:900px; margin:0 auto; line-height:1.5;">
    <p style="margin:0.4rem 0;">Co-organized with Meta, Google, CTU Prague, ENPC ParisTech, NVIDIA, Niantic, KAIST, and others.</p>
    <p style="margin:0.4rem 0;">BOP is a collaborative benchmark for 6D pose estimation. I joined the organizers in 2024, contributing to the annotation tool in the BOP toolkit, dataset collection, and toolkit maintenance. The benchmark has recently expanded to unseen 6D pose estimation, closely aligned with my PhD research.</p>
  </div>
  <div class="project-meta" style="margin-top:0.9rem;">
    <div style="margin:0.3rem 0;">
      <strong>Published Papers:</strong>
      <a href="{{ page.url | relative_url }}#bop-2024-report" style="background:#e0e0e0; color:#000; padding:0.25em 0.6em; border-radius:0.35em; text-decoration:none; display:inline-flex; align-items:center; gap:0.35rem; font-size:0.9em;">BOP 2024 Report</a>
    </div>
    <div style="margin:0.3rem 0; display:inline-flex; gap:0.4rem; flex-wrap:wrap;">
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">6D Pose</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Unseen Objects</span>
      <span style="background:#f0f0f0; padding:0.25em 0.6em; border-radius:999px; font-size:0.9em;">Benchmarking</span>
    </div>
  </div>
</div>


</section>

## CV {#cv}

## Teaching {#teaching}
