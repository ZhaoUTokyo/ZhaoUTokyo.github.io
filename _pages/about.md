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

# 📌 Short Bio (<a href="CV/FanZHAO_CV.pdf">**CV**)
**Dr. Fan Zhao** is a Postdoctoral Researcher at the Department of Urban Informatics, Shenzhen University, where he collaborates with the research group of Prof. Qingquan Li, an Academician of the Chinese Academy of Engineering. He received his Ph.D. and M.E.S. from the Environmental Informatics and Sensing Laboratory at the University of Tokyo in March 2025 and March 2022, respectively.  

His research focuses on addressing environmental challenges through advanced sensing technologies and information science. By integrating multi-source data acquisition with artificial intelligence and computational methods, his work aims to enhance environmental monitoring and analysis.  

He utilizes commercial unmanned aerial vehicles, self-developed surface unmanned systems, and satellite remote sensing imagery to interpret and analyze environmental systems across marine, underwater, agricultural, and urban environments. His research seeks to improve monitoring efficiency, reduce operational costs, increase analytical accuracy, and reveal previously unobservable environmental information through data-driven approaches.  
<br>

# 🔥 News
- *2026.02.10*:  🎉🎉 One **first-author** paper on UAV-based monitoring of benthic organisms in the coastal lagoon of Lake Hamana, Japan, has been accepted by ***Remote Sensing in Ecology and Conservation***. (<a href="[https://www.sciencedirect.com/science/article/pii/S0924271626000559](http://doi.org/10.1002/rse2.70066)" target="_blank">link</a>)  
- *2026.02.09*: &nbsp;🎉🎉 One **first-author** paper on a self-developed amphibious UAV and its practical applications in inland rivers, lakes, and marine environments has been accepted by ***Marine Environmental Research***. (<a href="https://doi.org/10.1016/j.marenvres.2026.107911" target="_blank">link</a>)  
- *2026.02.04*: &nbsp;🎉🎉 Our paper on efficient and robust floating plastic debris monitoring has been accepted by ***Expert Systems with Applications***. (<a href="https://doi.org/10.1016/j.eswa.2026.131552" target="_blank">link</a>)  
- *2025.11.25*: &nbsp;🎉🎉 One co-authored paper on coral condition assessment and *Drupella* sp. identification using point cloud semantic segmentation has been published in ***Marine Pollution Bulletin***. (<a href="https://doi.org/10.1016/j.marpolbul.2025.119072" target="_blank">link</a>)  
<br>


# 📜 Publications 
<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">RSEC 2026</div>
    </div>
    <img src='images/isprs2026.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [Deep learning‐based super‐resolution reconstruction and improved YOLOv9 for efficient benthos detection: a case study at Lake Hamana, Japan]([https://www.sciencedirect.com/science/article/pii/S0924271625004885?dgcid=coauthor](http://doi.org/10.1002/rse2.70066))

  ***Zhao, F.****, Ma, B., Xi, D., Wang, J., Chen, Y., Liu, Y., Shao, X., Zhang, M., Zhang, G., Chen, J. & Mizuno, K.

  <em>Remote Sensing in Ecology and Conservation，2026.</em> 

  <div class="paper-links">
    <a class="paper-link" href="https://www.sciencedirect.com/science/article/pii/S0924271625004885?dgcid=coauthor" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
  </div>
  </div>
</div>


<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">ESSD 2025</div>
      <div class="badge spotlight-badge">IEEE GRSS Data Fusion Contest 2025</div>
    </div>
    <img src='images/overall.jpg' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [Bright: a globally distributed multimodal building damage assessment dataset with very-high-resolution for all-weather disaster response](https://essd.copernicus.org/articles/17/6217/2025/essd-17-6217-2025.html)

  Hongruixuan Chen, **Jian Song**, Olivier Dietrich, Clifford Broni-Bediako, Weihao Xuan, Junjue Wang, Xinlei Shao, Yimin Wei, Junshi Xia, Cuiling Lan, Konrad Schindler, Naoto Yokoya

  <em>Earth System Science Data (ESSD), 2025.</em> 
  <span style="color: #ff4500; font-weight: bold;">*IEEE GRSS Data Fusion Contest 2025 Official Dataset* </span>

  <div class="paper-links">
    <a class="paper-link" href="https://essd.copernicus.org/articles/17/6217/2025/essd-17-6217-2025.html1" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/BRIGHT" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/BRIGHT" title="Data">
      <i class="fas fa-database"></i> Data
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">NeurIPS 2024</div>
      <div class="badge spotlight-badge">Spotlight</div>
    </div>
    <img src='images/SynRS3D.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [SynRS3D: A Synthetic Dataset for Global 3D Semantic Understanding from Monocular Remote Sensing Imagery](https://arxiv.org/abs/2406.18151)

  **Jian Song**, Hongruixuan Chen, Weihao Xuan, Junshi Xia, Naoto Yokoya

  In <em>Proc. 38th Annual Conference on Neural Information Processing Systems (Datasets and Benchmarks Track), 2024.</em> 
  <span style="color: #ff4500; font-weight: bold;">*Spotlight Paper* [top 3.08%]</span>

  <div class="paper-links">
    <a class="paper-link" href="https://jtrneo.github.io/SynRS3D/" title="Project Page">
      <i class="fas fa-home"></i> Project Page
    </a>
    <a class="paper-link" href="https://arxiv.org/abs/2406.18151" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/JTRNEO/SynRS3D" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
    <a class="paper-link" href="https://zenodo.org/records/13905264" title="Data">
      <i class="fas fa-database"></i> Data
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">TGRS 2024</div>
      <div class="badge spotlight-badge">ESI Hot Paper / ESI Highly Cited Paper</div>
    </div>
    <img src='images/ChangeMamba.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [ChangeMamba: Remote Sensing Change Detection with Spatio-Temporal State Space Model](https://ieeexplore.ieee.org/document/10565926)

  Hongruixuan Chen<span>*</span>, <strong>Jian Song<span>*</span></strong>, Chengxi Han, Junshi Xia, Naoto Yokoya

  <em>IEEE Transactions on Geoscience and Remote Sensing (**TGRS**), 2024.</em> 
  <span style="color: #ff4500; font-weight: bold;">*ESI Hot Paper / ESI Highly Cited Paper*</span>

  <div class="paper-links">
    <a class="paper-link" href="https://ieeexplore.ieee.org/document/10565926" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/MambaCD" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">WACV 2024</div>
    </div>
    <img src='images/SyntheWorld.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [SyntheWorld: A Large-Scale Synthetic Dataset for Land Cover Mapping and Building Change Detection](https://openaccess.thecvf.com/content/WACV2024/html/Song_SyntheWorld_A_Large-Scale_Synthetic_Dataset_for_Land_Cover_Mapping_and_WACV_2024_paper.html)

  **Jian Song**, Hongruixuan Chen, Naoto Yokoya

  In <em>Proc. IEEE/CVF Winter Conference on Applications of Computer Vision, 2024.</em> 

  <div class="paper-links">
    <a class="paper-link" href="https://openaccess.thecvf.com/content/WACV2024/html/Song_SyntheWorld_A_Large-Scale_Synthetic_Dataset_for_Land_Cover_Mapping_and_WACV_2024_paper.html" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/JTRNEO/SyntheWorld" title="Data">
      <i class="fas fa-database"></i> Data
    </a>
  </div>
  </div>
</div>

<div class='paper-box'>
  <div class='paper-box-image'>
    <div class="badges">
      <div class="badge conference-badge">ISPRS 2024</div>
    </div>
    <img src='images/exchange.png' alt="sym" width="100%">
  </div>
  <div class='paper-box-text' markdown="1">
  [Exchange Means Change: An Unsupervised Single-Temporal Change Detection Framework Based on Intra- and Inter-Image Patch Exchange](https://www.sciencedirect.com/science/article/abs/pii/S092427162300309X)

  Hongruixuan Chen, **Jian Song**, Chen Wu, Bo Du, Naoto Yokoya

  <em>ISPRS Journal of Photogrammetry and Remote Sensing, 2023.</em> 

  <div class="paper-links">
    <a class="paper-link" href="https://www.sciencedirect.com/science/article/abs/pii/S092427162300309X" title="Paper">
      <i class="fas fa-file-pdf"></i> Paper
    </a>
    <a class="paper-link" href="https://github.com/ChenHongruixuan/I3PE" title="Code">
      <i class="fas fa-file-code"></i> Code
    </a>
  </div>
  </div>
</div>

<!-- Journal Articles -->
- [Generalized Few-Shot Semantic Segmentation in Remote Sensing: Challenge and Benchmark](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=8859), C. Broni-Bediako, J. Xia, **J. Song**, H. Chen, M. Siam, N. Yokoya, ***IEEE GRSL 2024***

- [ObjFormer: Learning Land-Cover Changes From Paired OSM Data and Optical High-Resolution Imagery via Object-Guided Transformer](https://ieeexplore.ieee.org/document/10551264), H. Chen, C. Lan, **J. Song**, C. Broni-Bediako, J. Xia, N. Yokoya, ***IEEE TGRS 2024***

- [Deep Learning for Multi-Label Classification of Coral Conditions in the Indo-Pacific via Underwater Photogrammetry](https://onlinelibrary.wiley.com/doi/10.1002/aqc.4241), X. Shao, H. Chen, K. Magson, J. Wang, **J. Song**, J. Chen, J. Sasaki, ***Aquatic Conservation 2024***

<!-- Conference Papers -->
- [OpenEarthMap Benchmark Suite and Its Applications](https://ieeexplore.ieee.org/abstract/document/10640801), N. Yokoya, J. Xia, C. Broni-Bediako, **J. Song**, H. Chen, ***IGARSS 2024*** (Oral Presentation)

- [Change Detection Between Optical Remote Sensing Imagery and Map Data via Segment Anything Model (SAM)](https://ieeexplore.ieee.org/document/10642789), H. Chen, **J. Song**, N. Yokoya, ***IGARSS 2024*** (Oral Presentation)

- [Disaster Detection from SAR Images with Different Off-Nadir Angles Using Unsupervised Image Translation](https://ceur-ws.org/Vol-3207/paper3.pdf), **J. Song**, B. Adriano, N. Yokoya, ***CDCEO Workshop at IJCAI 2022***


<!-- Education Section
<h2>🎓 Education</h2>
<ul>
  <li>
    <strong>The University of Tokyo, Chiba, Japan</strong>  
    <br><em>Oct. 2021 – Present</em>  
    Ph.D. Candidate in Engineering (Major: Complexity Science and Engineering)  
    <br>Research Topic: Synthetic data-driven 3D semantic reconstruction in remote sensing
  </li>
  <li>
    <strong>Waseda University, Fukuoka, Japan</strong>  
    <br><em>Oct. 2019 – Mar. 2021</em>  
    Master of Engineering (Major: Information Engineering)  
    <br>Research Topic: Flow-guided video object detection
  </li>
  <li>
    <strong>Wuhan University, Wuhan, China</strong>  
    <br><em>Sep. 2018 – Jun. 2021</em>  
    Master of Engineering (Major: Software Engineering)  
    <br>Research Topic: Remote sensing image semantic segmentation
  </li>
  <li>
    <strong>Fujian Agriculture and Forestry University, Fuzhou, China</strong>  
    <br><em>Sep. 2011 – Jun. 2015</em>  
    Bachelor of Agriculture (Major: Forestry Information Engineering)
  </li>
</ul> -->

<!-- Employment History
<h2>💼 Employment History</h2>
<ul>
  <li>
    <strong>The University of Tokyo, Tokyo, Japan</strong>  
    <br><em>Oct. 2021 – May 2024</em>  
    Research Assistant  
    <br>Supervisor: Prof. Naoto Yokoya
  </li>
  <li>
    <strong>RIKEN AIP, Tokyo, Japan</strong>  
    <br><em>Apr. 2021 – Present</em>  
    Research Part-timer  
    <br>Supervisor: Prof. Naoto Yokoya
  </li>
  <li>
    <strong>Inception Institute of Artificial Intelligence, Abu Dhabi, UAE</strong>  
    <br><em>Mar. 2019 – Aug. 2019</em>  
    Research Intern  
    <br>Supervisor: Dr. Fan Zhu
  </li>
  <li>
    <strong>Land Satellite Remote Sensing Application Center, Beijing, China</strong>  
    <br><em>May 2018 – Sep. 2018</em>  
    Research Intern  
    <br>Supervisor: Dr. Yuhang Gan
  </li>
</ul> -->


<!-- Content Section -->
<p style="text-align: center;">
  <div id="clustrmaps-widget" style="max-width: 20%; margin: 0 auto;">
    <script 
      type="text/javascript" 
      id="clustrmaps" 
      src="//clustrmaps.com/map_v2.js?d=uTY2AY6y6-cxWrNfdFwh2S1zspQywC0Y_DfDGQVQclc&cl=ffffff&w=a" 
      async>
    </script>
    <noscript>
      <a href="https://clustrmaps.com/site/1bj1k" title="Visitor Map">
        <img 
          src="//clustrmaps.com/map_v2.png?d=uTY2AY6y6-cxWrNfdFwh2S1zspQywC0Y_DfDGQVQclc&cl=ffffff&w=a" 
          alt="Visitor Map" 
          style="max-width: 20%; height: auto;">
      </a>
    </noscript>
  </div>
  <p style="text-align:center;">
    &copy; Fan ZHAO | Last updated: March 2025
  </p>     
</p>

<!-- Footer -->
<footer class="footer" style="text-align: center;">
  <div class="container">
    <div class="content has-text-centered">
      <p style="color: #4A4A4A;">
        This website template is borrowed from 
        <a href="https://github.com/RayeRen/acad-homepage.github.io" style="color: #3273DC;">AcadHomepage</a>
      </p>
    </div>
  </div>
</footer>

