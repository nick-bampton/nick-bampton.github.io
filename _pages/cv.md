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
* Ph.D in Electrical Engineering, Virginia Polytechnic Institute and State University, 2027 (expected)
* B.S. in Mathematics, Virginia Polytechnic Institute and State University, 2022
* B.S. in Electrical Engineering, Virginia Polytechnic Institute and State University, 2022

Research Experience
======
Research Assistantship, January 2025 - Present<br>
\- University of Illinois, Urbana IL<br> 	
\- Modeled camera motion using the Fourier transform for background reconstruction in small target detection. Specifically modeled the data as a blind demixing problem where images are convolved with a motion tensor and analyzed the region of convergence for the space of initializations.

Research Assistantship, September 2023 - January 2025<br>
>University of Illinois, Urbana IL<br> 	
>Derived convergence results for dynamic programming algorithms in small target detection. Specifically unified dynamic programming algorithms from a graph theory perspective and derived the inverse relationship between location uncertainty and existence uncertainty. 

Summer Internship, May 2023 - September 2023<br>
Sandia National Laboratory, Albuquerque NM<br> 	
Modeled video backgrounds using topological properties for small infrared target detection. Specifically used the persistent homology of a surface, computed using the contour tree, to construct a background model and spatially filter out foreground elements. Mathematically demonstrated the class of domain operations for which the persistent homology is invariant.  

Summer Internship, May 2019 - September 2021<br>
Naval Surface Warfare Center Dahlgren Division, Dahlgren VA<br> 	
Applied spectral graph theory techniques for low angle radar clutter comparisons.  Reduced the dimensionality of video data through graph encoding and compared using graph metrics, primarily the Wasserstein metric and various spectral methods from the Eigendecomposition of the graph laplacian. 

  
Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
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
