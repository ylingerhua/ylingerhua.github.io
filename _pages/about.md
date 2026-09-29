---
permalink: /
title: 
excerpt: 
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hi, this is Yanling. I'm passionate about cutting-edge research in **3D Reconstruction and Generation**, as well as **Extended Reality (XR)**. My expertise spans a broad range of topics, including generative models (GANs, diffusion models), 3D vision techniques (NeRF, 3D Gaussian Splatting, parametric human modeling, SLAM, and MVS), as well as XR application development. I’m open to diverse opportunities in these fields.


{% comment %} News section hidden; remove this comment wrapper to show it again.
## News!

**[2025/06/15]** Graduated from Lund University.  
**[2025/01/20]** Started as a **Master’s thesis worker** at [Sony Nordic](https://www.linkedin.com/company/sony-europe/posts/?feedView=all).  
**[2024/06/20]** Began an **internship** at [Kunlun Wanwei](https://www.kunlun.com/en/), focusing on **3D human motion generation**.  
**[2023/08/15]** Moved to **Lund, Sweden** to begin my **Master’s studies** at [Lund University](https://www.lunduniversity.lu.se/).  
**[2023/04/01]** Admitted to the **VR/AR program** at [Lund University](https://www.lunduniversity.lu.se/).
{% endcomment %}

## Research Experience

<!-- Generated from _publications/, newest first. Card images come from each file's `thumbnail` field. -->
{% assign publications = site.publications | sort: "date" | reverse %}
{% for pub in publications %}
<div class="project-card">
  {%- if pub.thumbnail %}
  <div class="project-card__media">
    <a href="{{ pub.url }}"><img src="{{ pub.thumbnail }}" alt="" loading="lazy"></a>
  </div>
  {%- endif %}
  <div class="project-card__body">
    <h3 class="project-card__title"><a href="{{ pub.url }}">{{ pub.title }}</a></h3>
    <p class="project-card__authors">{{ pub.authors }}</p>
    <p class="project-card__venue">{% if pub.category == "masterthesis" %}Master's thesis, {% endif %}<i>{{ pub.venue }}</i>, {{ pub.date | date: "%Y" }}</p>
    <a href="{{ pub.paperurl }}" target="_blank"><i class="fas fa-fw fa-file-pdf"></i>PDF</a>
    {%- if pub.codeurl %} / <a href="{{ pub.codeurl }}" target="_blank"><i class="fab fa-fw fa-github"></i>Code</a>{% endif %}
  </div>
</div>
{% endfor %}

## Professional Experience

<div class="project-card project-card--compact">
  <div class="project-card__media">
    <img src="/images/thumbs/co_speech_pose.jpg" alt="Generated talking poses" loading="lazy">
  </div>
  <div class="project-card__body">
    <h3 class="project-card__title">Talking Pose Generation</h3>
    <p>Generating body and hand gestures driven by speech, carried out independently. I explored two approaches: motion retrieval and end-to-end motion generation.</p>
    <a href="/huahua/End2end%20motion%20generation.html" target="_blank"><i class="fas fa-fw fa-globe"></i>Project Page</a>
  </div>
</div>
<div class="project-card project-card--compact">
  <div class="project-card__media">
    <img src="/images/thumbs/nerf.jpg" alt="Semantic NeRF renderings of a street scene" loading="lazy">
  </div>
  <div class="project-card__body">
    <h3 class="project-card__title">Semantic NeRF in Unbounded Scenes for Autonomous Driving</h3>
    <p>Semantic auto-labeling for autonomous-driving scenes, carried out independently. I used NeRF, which performs strongly at novel view synthesis, to render multi-view images and obtain semantic labels.</p>
    <a href="/huahua/Semantic%20Nerf%20in%20unbounded%20scene%20for%20autonomous%20driving%20scene.html" target="_blank"><i class="fas fa-fw fa-globe"></i>Project Page</a>
  </div>
</div>
<div class="project-card project-card--compact">
  <div class="project-card__media">
    <video src="/images/bunny-rgb.mp4" poster="/images/thumbs/bunny-rgb.jpg" autoplay loop muted playsinline aria-label="Rotating generated 3D bunny asset"></video>
  </div>
  <div class="project-card__body">
    <h3 class="project-card__title">3D Generation for Game Assets</h3>
    <p>Research on constructing 3D models of game assets.</p>
    <a href="/huahua/3D%20generation.html" target="_blank"><i class="fas fa-fw fa-globe"></i>Project Page</a>
  </div>
</div>


<!-- ## Personal
I spend my spare time in reading, watching movies and traveling. Recently I am reading some books related to -->
## Personal
I am committed to learning endlessly, living authentically, and loving deeply. I believe the meaning of life is to experience. This is my favourite quote:

> *"Sing like no one is listening.  
> Love like you’ve never been hurt.  
> Dance like nobody’s watching,  
> And live like it’s heaven on earth."* 


## Contact
E-mail: yanlinghua[AT]cs.au.dk

<!-- <a href="https://info.flagcounter.com/dTp3"><img src="https://s11.flagcounter.com/map/dTp3/size_s/txt_000000/border_CCCCCC/pageviews_0/viewers_0/flags_0/" alt="Flag Counter" border="0"></a> -->

