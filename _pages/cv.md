---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Ph.D in Physics Based Animation, Dapartment of Computer Science and Engineering, IIT Delhi 2027 (expected)
* M.S. by Research in Computer Science and Engineering, IIT Indore, 2022
* B. Tech. in Computer Science and Engineering, Rajkiya Engineering College Kannauj, AKTU, 2026

Research Projects
======
* Spetember 2024 - April 2026: Dynamic Wrinkling on Coarsely-Meshed Cloth
  * Proposed a dynamic cloth simulation framework that captures high-frequency wrinkling on coarse meshes using
two-way coupling between coarse mesh simulation and wrinkle parameters in a physically consistent manner.
  * Introduced a time-coherent wrinkle reconstruction algorithm that ensures temporal consistency in wrinkled mesh.
  * Supervisor: Professor Rahul Narain

* December 2022 - August 2024: LI Fluids: Improving the stability of Covector Fluids
  * Proposed a Line-Integral advection scheme that enforces Kelvin’s circulation theorem in fluid flow.
  * Achieves better stability while preserving rotational dynamics comparable to existing covector advection.
  * Introduced a stabilization heuristic based on the relative area (2D) and volume (3D) change of the Eulerian grid cells
to ensure average vorticity conservation between the backtraced and current discrete grid cells.
  * Supervisor: Professor Rahul Narain

* August 2021 – July 2022: Heart rate (HR) estimation from face videos using remote PPG
  * Introduced a dense MLP feature embedding layer that transforms noisy temporal signals into robust feature
embeddings, then applied global self-attention to filter out illumination and motion noise.
  * The filtered signal is used to predict heart rate from webcam videos.
  * Achieved a Mean Absolute Error (MAE) of 2.91 Beats Per Minute.
  * Supervisor: Professor Puneet Gupta
  
Skills
======
* Languages
  * C++, Python, C, GLSL, MATLAB
* Libraries & APIs
  * OpenGL, Eigen, OpenMP, NumPy, SciPy, PyTorch
* Tools & Platforms
  * CMake, Git, Linux (Arch/Ubuntu), Blender (bpy scripting), LaTeX

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->
  
<!-- Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->
<!--   
Service and leadership
======
* Currently signed in to 43 different slack teams -->
