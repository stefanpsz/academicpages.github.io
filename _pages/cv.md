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
------
* Ph.D in Medical Image Analysis, Imperial College London, 2015
* M.Sc. in Engineering Sciences, Pontificia Universidad Cat&oacute;lica de Chile, 2007
* Computer Engineering, Pontificia Universidad Cat&oacute;lica de Chile, 2007


Work experience
------
* 2015-: Research Fellow
  * The University of Nottingham, Nottingham, UK
  * Line Managers: Prof. Rob Dineen and Prof. Nikola Sprigg (2015-2018)
  * Line Managers: Prof. Rob Dineen and Prof. Dorothee Auer (2018-2020)
  * Line Manager: Dr. Chris Tench (2020-)
* 2014-2015: Research Assistant
  * Imperial College London, London, UK
  * Supervisor: Prof. Daniel Rueckert
* 2007-2010: Software Engineer and Project Manager
  * Cursor, Santiago, Chile
  

Training
------
* Dec 2017: Preparing to Teach in Higher Education Certificate, University of Nottingham, UK
  * Nov 2017: Small Group Teaching
  * Jun 2017: Lecturing for Learning
  * May 2017: Foundations of Teaching in Higher Education
  * Apr 2017: Preparing to Teach in Higher Education
* Sep 2017: GCP (Good Clinical Practice) refresher, NIHR, UK
* Dec 2015: GCP (Good Clinical Practice), NIHR, UK


Awards
------
* 2019: University of Nottingham International Collaboration Fund Award to finance a one-month research visit to Universidad de Valpara&iacute;so, Chile.
* 2012: Runner-up in the Google PhD Poster Competition (2nd year category), Imperial College London.
* 2009: CONICYT-Becas Chile scholarship for Doctoral studies, CONICYT.
  

Other
------
* Grant reviews
  * Projects for Initiation in Research 2019, FONDECYT
* Journal paper reviews
  * Computers in Biology and Medicine
  * IEEE Journal of Biomedical and Heath Informatics
  * IEEE Transactions on Medical Imaging
  * Medical Physics
* Member of the organising comitee and travel grants administrator
  * Chile-Global Seminars UK.


Skills
------
* Operating Systems
  * GNU/Linux
  * MacOS
  * Windows
* Programming Languages
  * C/C++
  * Java
  * Matlab
  * Python
  * Bash
  * R
* Databases
  * MySQL
  * PostgreSQL
* Tools
  * Eclipse
  * Microsoft Office
  * LaTEX

  
Publications
------
  <div>
  <p><h4>Peer-reviewed journal publications</h4></p>
  <ul>
  {% for post in site.publications-journal reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>

  <div>
  <p><h4>Preprint publications</h4></p>
  <ul>
  {% for post in site.publications-preprint reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>

  <div>
  <p><h4>Conference publications</h4></p>
  <ul>
  {% for post in site.publications-conference reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>

  <div>
  <p><h4>Conference abstracts</h4></p>
  <ul>
  {% for post in site.publications-abstract reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>

  <div>
  <p><h4>Thesis</h4></p>
  <ul>
  {% for post in site.publications-thesis reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>
  
  <div>
  <p><h4>Other</h4></p>
  <ul>
  {% for post in site.publications-other reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>
  </div>

Teaching
======
  <ul>
  {% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}
  </ul>


Languages
======
* Spanish
  * Native
* English
  * Professional working proficiency
  * Score 8.0 IELTS (Academic), June 2014
* Polish
  * Limited working proficiency
