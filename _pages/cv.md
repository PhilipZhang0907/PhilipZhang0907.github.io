---
layout: archive
titile: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* Master of CS in University of Science and Technology of China, 2024
* Bachelor of CS in University of Science and Technology of China, 2021

Research Experiences
======
* Human Pose Estimation Using a Full-Body Pressure-Sensing Garment
  * Precise Pervasive Lab, USTC
  * Advisor: Prof. Xiaohui Cai
    * Generated a dataset consists of full-body pressure data and 3D human poses. The dataset is the first one that contains large areas of pressure distributions on body surfaces and corresponding 3D human pose labels.
    * Compared with existing environmental systems, our wearable system records pressure data with different characteristics. To design suitable algorithm for the wearable system, we explored deeper how full-body pressure data are related to human movements and analyzed the principle of full-body pressure data.
    * Designed and implemented a kinematics-based pose estimation algorithm which reconstruct 3D human poses by predicting joint rotations. The algorithm was examined using leave-one-out cross validation. The results demonstrated the feasibility of full-body pressure sensing system in 3D human pose estimation.

* Full-Body Pressure-Sensing System Development (the Smart Garment)
  * Precise Pervasive Lab, USTC
  * Advisor: Prof. Xiaohui Cai
    * Participated in the development of the system hardware, including sewing and circuits connecting.
    * To observe 2D matrix-shape pressure data more directly, I developed a configurable visualization system using Visualization Toolkit (VTK). The system maps 2D matrix-shape pressure data to a 3D human model. It could adapt to different data arrangements and data sizes by updating a configuration file. [Demo]
    * To explore the potential uses of the system, we generated a dataset consist of full-body pressure data and human activity tags. A ResNet18 network was used to run classification tasks on the dataset. The results demonstrated the feasibility of the full-body pressure sensing system in human activity recognition.

* Wearable fNIRS System for Microcirculation Monitoring
  * Precise Pervasive Lab, USTC
  * Advisor: Prof. Xiaohui Cai
    * Implemented a prototype microcirculation monitoring system based on fNIRS method. The system monitors microcirculation by calculating light attenuation caused by hemoglobin (HbO2) and deoxy-hemoglobin (Hb).
    * The prototype system is used for technical validation of large-area arrayed fNIRS systems, which have potential applications in preventing vascular diseases and muscle strain.

* Cardiac Fiber Visualization System Using DT-MRI Images
  * Undergraduate Final Year Project in USTC 
  * Advisor: Prof. Xiaohui Cai
    * Implemented a cardiac muscle fiber visualization system using diffusion tensor MRI (DT-MRI) images. The system models and visualizes cardiac muscle fibers using streamline tracking method or tensor deflection method.
    * Implemented a hierarchical clustering algorithm which models cardiac muscle fibers using the similarities of the tracked points. Similarities are calculated using both the locations and the fiber angles of the tracked points.
  
Honors & Awards
======
* First Class Academic Scholarship for Master Student (2023)
* First Class Academic Scholarship for Master Student (2022)
* First Class Academic Scholarship for Master Student (2021)
* 2020 Scholarship for Outstanding Students (Bronze Adward)

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
<!-- Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams
-->
