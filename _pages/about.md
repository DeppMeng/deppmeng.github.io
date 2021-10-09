---
permalink: /
title: "Hi!"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Depu Meng is a forth-year Joint-Ph. D. student at University of Science and Technology and Microsoft Research Asia.
His advisors are [Dr. Jingdong Wang](https://jingdongwang2017.github.io/) and [Prof. Houqiang Li](http://staff.ustc.edu.cn/~lihq/en/).
He interned at Microsoft Research Asia during 2017-2018, and 2019-2021. He is currently a research intern at Meituan.

His research interests include *2D object detection/pose estimation, unsupervised representation learning, 3D object detection, motion prediction*, etc. He has great passion in computer vision research.

Education
======
* *Sept. 2018 - Jun. 2023 (expected)*  
  **Ph.D. student**  
  School of Information Science and Technology, major in Automation  
  University of Science and Technology of China  
  Supervisor: Dr. Jingdong Wang and Prof. Houqiang Li
* *Sept. 2014 - Jun. 2018*  
  **B.S. student**  
  School of the Gifted Young (SCGY), major in Electrical Engineering  
  University of Science and Technology of China

Work Experience
======
* *Aug. 2021 - present*  
  **Research Intern**  
  Autonomous Delivery Group, Meituan  
  Mentor: Dr. Changqiang Yu
* *Jul. 2019 - Jul. 2021*  
  **Research Intern**  
  Visual Computing Group, Microsoft Research Asia  
  Mentor: Dr. Jingdong Wang
* *Jul. 2017 - Jul. 2018*  
  **Research Intern**  
  Visual Computing Group, Microsoft Research Asia  
  Mentor: Dr. Jingdong Wang

Publication       {#publications}
======

{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
