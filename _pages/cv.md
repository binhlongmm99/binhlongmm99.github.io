---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

<link rel="stylesheet" href="{{ base_path }}/assets/css/cv.css">

<div class="cv-page">

<section class="cv-section">
  <h2 class="cv-section-title">Education</h2>
  <ul class="cv-list">
    <li class="cv-edu-item">
      <span class="cv-edu-main"><strong>Ph.D. Candidate</strong>, Queensland University of Technology (QUT)</span>
      <span class="cv-edu-date">2024 – Present</span>
    </li>
    <li class="cv-edu-item">
      <span class="cv-edu-main"><strong>M.S. in Computer Science</strong>, Hanoi University of Science and Technology (HUST)</span>
      <span class="cv-edu-date">2021 – 2023</span>
    </li>
    <li class="cv-edu-item">
      <span class="cv-edu-main"><strong>B.S. in Information Technology (Honours)</strong>, Hanoi University of Science and Technology (HUST)</span>
      <span class="cv-edu-date">2017 – 2021</span>
    </li>
    <li class="cv-edu-item">
      <span class="cv-edu-main"><strong>Mathematics Specialized Class</strong>, Hanoi Amsterdam High School for the Gifted</span>
      <span class="cv-edu-date">2014 – 2017</span>
    </li>
  </ul>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Work Experience</h2>

  <h3 class="cv-subsection-title">Research Experience</h3>

  <div class="cv-job">
    <div class="cv-job-header">
      <p class="cv-job-role">PhD Researcher</p>
      <span class="cv-job-date">Mar 2024 – Present</span>
    </div>
    <p class="cv-job-org">CSIRO Robotics &amp; QUT</p>
    <ul class="cv-job-bullets">
      <li>Research area: 3D scene understanding, robot perception, and embodied AI.</li>
      <li>Develop open-vocabulary 3D scene representations using Gaussian Splatting and vision-language models.</li>
      <li>Design online semantic mapping and scene graph frameworks for robotic perception and manipulation.</li>
      <li>Develop affordance-aware 3D representations for functional robotic manipulation.</li>
    </ul>
  </div>

  <div class="cv-job">
    <div class="cv-job-header">
      <p class="cv-job-role">Research Assistant</p>
      <span class="cv-job-date">Oct 2019 – Oct 2023</span>
    </div>
    <p class="cv-job-org">Modelling, Simulation and Optimization Laboratory – HUST</p>
    <ul class="cv-job-bullets">
      <li>Research area: evolutionary computation, multitask optimization.</li>
      <li>Develop optimization algorithms for graph-based combinatorial optimization problems.</li>
    </ul>
  </div>

  <h3 class="cv-subsection-title">Industry Experience</h3>

  <!-- <div class="cv-job">
    <div class="cv-job-header">
      <p class="cv-job-role">Computer Vision Intern</p>
      <span class="cv-job-date">Mar 2023 – May 2023</span>
    </div>
    <p class="cv-job-org">iCOMM Media &amp; Tech, Jsc</p>
    <ul class="cv-job-bullets">
      <li>Developed computer vision solutions for image classification, object detection, and segmentation.</li>
      <li>Fine-tuned CLIP models for traffic participant and vehicle attribute recognition.</li>
      <li>Evaluated Segment Anything (SAM) for traffic scene segmentation.</li>
    </ul>
  </div> -->

  <div class="cv-job">
    <div class="cv-job-header">
      <p class="cv-job-role">AI Engineer Intern</p>
      <span class="cv-job-date">Mar 2021 – Feb 2022</span>
    </div>
    <p class="cv-job-org">Toshiba Software Development Vietnam</p>
    <ul class="cv-job-bullets">
      <li>Developed optimization solutions for industrial scheduling and energy management using PuLP and Gurobi.</li>
      <li>Designed heuristic and metaheuristic algorithms for combinatorial optimization of water-pumping schedules.</li>
      <li>Built data analytics pipelines and time-series forecasting models for passenger flow prediction.</li>
    </ul>
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Skills</h2>
  <ul class="cv-list">
    <li class="cv-skill-item">
      <span class="cv-skill-label"><strong>Programming languages</strong></span>
      <span class="cv-skill-value">Python, C/C++, Java</span>
    </li>
    <li class="cv-skill-item">
      <span class="cv-skill-label"><strong>Frameworks &amp; Libraries</strong></span>
      <span class="cv-skill-value">PyTorch, OpenCV, Open3D, ROS</span>
    </li>
    <li class="cv-skill-item">
      <span class="cv-skill-label"><strong>Tools</strong></span>
      <span class="cv-skill-value">Git, Linux, Conda, COLMAP, Nerfstudio, Gurobi</span>
    </li>
    <li class="cv-skill-item">
      <span class="cv-skill-label"><strong>Languages</strong></span>
      <span class="cv-skill-value">Vietnamese (Native), English (IELTS 7.5)</span>
    </li>
  </ul>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Publications</h2>
  <div class="cv-compact-list">
    {% assign pubs = site.publications | sort: "date" | reverse %}
    {% for post in pubs %}
      {% include archive-single-cv-compact.html %}
    {% endfor %}
  </div>
</section>

<section class="cv-section">
  <h2 class="cv-section-title">Teaching</h2>
  <div class="cv-compact-list">
    {% assign courses = site.teaching | sort: "date" | reverse %}
    {% for post in courses %}
      {% include archive-single-cv-compact.html %}
    {% endfor %}
  </div>
</section>

</div>
