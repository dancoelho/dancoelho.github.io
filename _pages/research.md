---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
redirect_from:
  - /resume
---

Brief descriptions for each of the few works I've developed so far.

<style>
/* Style the Image Used to Trigger the Modal */
#myImg {
  border-radius: 5px;
  cursor: pointer;
  transition: 0.3s;
}

#myImg:hover {opacity: 0.7;}

/* The Modal (background) */
.modal {
  display: none; /* Hidden by default */
  position: fixed; /* Stay in place */
  z-index: 1; /* Sit on top */
  padding-top: 100px; /* Location of the box */
  left: 0;
  top: 0;
  width: 100%; /* Full width */
  height: 100%; /* Full height */
  overflow: auto; /* Enable scroll if needed */
  background-color: rgb(0,0,0); /* Fallback color */
  background-color: rgba(0,0,0,0.9); /* Black w/ opacity */
}

/* Modal Content (Image) */
.modal-content {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
}

/* Caption of Modal Image (Image Text) - Same Width as the Image */
#caption {
  margin: auto;
  display: block;
  width: 80%;
  max-width: 700px;
  text-align: center;
  color: #ccc;
  padding: 10px 0;
  height: 150px;
}

/* Add Animation - Zoom in the Modal */
.modal-content, #caption { 
  animation-name: zoom;
  animation-duration: 0.6s;
}

@keyframes zoom {
  from {transform:scale(0)} 
  to {transform:scale(1)}
}

/* The Close Button */
.close {
  position: absolute;
  top: 15px;
  right: 35px;
  color: #f1f1f1;
  font-size: 40px;
  font-weight: bold;
  transition: 0.3s;
}

.close:hover,
.close:focus {
  color: #bbb;
  text-decoration: none;
  cursor: pointer;
}

/* 100% Image Width on Smaller Screens */
@media only screen and (max-width: 700px){
  .modal-content {
    width: 100%;
  }
}
</style>

<!-- <a href="{{ base_path }}/files/Aula01.pdf" target="_blank"> Aula01</a> -->


<!-- ## [Transient Chaos in Potential and Nonpotential Swift-Hohenberg Dynamics](../_pages/404.md)

Gradients of the bifurcation parameter can induce stripe orientation in the Swift-Hohenberg dynamics. However, they face competition from boundary, bulk and geometric effects, and pattern alignment becomes an intrinsicate question.

<img src="{{ base_path }}/images/SH/SH23nonuniform.png" alt="SH23" style="width:40%;height:auto;">
<br><br> -->

<!-- ## [Gradient Pattern Analysis of patterns](../_pages/404.md)

Gradients of the bifurcation parameter can induce stripe orientation in the Swift-Hohenberg dynamics. However, they face competition from boundary, bulk and geometric effects, and pattern alignment becomes an intrinsicate question.

<img src="{{ base_path }}/images/SH/SH23nonuniform.png" alt="SH23" style="width:40%;height:auto;">
<br><br> -->


## Nonuniform forcing and stripe orientation in Swift-Hohenberg

{: style="text-align: justify" }
Gradients of the bifurcation parameter can induce stripe orientation in the Swift-Hohenberg dynamics. However, they face competition from boundary, bulk and geometric effects, and pattern alignment becomes an intricate question. [[more]](../_pages/404.md)

<img src="{{ base_path }}/images/SH/SH23nonuniform.png" alt="SH23" style="width:50%;height:auto;">
<br><br>


## Ramped Rayleigh-Bénard systems in circular geometries

{: style="text-align: justify" }
Several numerical works consider regular geometries when studying temperature gradients across a Rayleigh-Bénard convection cell. A numerical approach based on a finite-difference scheme is proposed for studying such system in a circular geometry maintaining second-order accuracy at the boundary conditions. [[more]](../_pages/404.md)


<!-- <img src="{{ base_path }}/images/RB/fig_0.png" alt="RB-cell-1" style="width:200px;height:200px;"> &nbsp;&nbsp;
<img src="{{ base_path }}/images/RB/fig_10.png" alt="RB-cell-2" style="width:200px;height:200px;"> &nbsp;&nbsp;
<img src="{{ base_path }}/images/RB/fig_100.png" alt="RB-cell-3" style="width:200px;height:200px;"> &nbsp;&nbsp;
<img src="{{ base_path }}/images/RB/fig_750.png" alt="RB-cell-4" style="width:200px;height:200px;"> -->
<img src="{{ base_path }}/images/RB/full.png" alt="RB-full" style="width:100%;height:auto;">
<br><br>


## Pattern formation in the Bénard-Marangoni convection

{: style="text-align: justify" }
Bénard-Marangoni convection exhibits square, hexagonal, and other peculiar patterns that can be modeled by the Knobloch equation. This fourth-order nonlinear evolution equation is derived _via_ multiple scales formalism and reproduces the main features of the full dynamics. [[more]](../_pages/knobloch.html)


<!-- <img src="{{ base_path }}/images/KN/KN1.png" alt="Benard-marangoni-cell-1" style="width:200px;height:200px;"> &nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/KN/KN2.png" alt="Benard-marangoni-cell-2" style="width:200px;height:200px;"> -->
<!-- Trigger the Modal -->

 <img src="{{ base_path }}/images/KN/full.png" alt="KN-full" style="width:50%;height:auto;">
<br><br>

<!-- <img id="myImg" src="{{ base_path }}/images/KN/full.png" alt="Snow" style="width:100%;height:auto"> -->

<!-- The Modal -->
<!-- <div id="myModal" class="modal"> -->

  <!-- The Close Button -->
<!-- <span class="close"> &times; </span> -->

  <!-- Modal Content (The Image) -->
  <!-- <img class="modal-content" id="img01"> -->

  <!-- Modal Caption (Image Text) -->
  <!-- <div id="caption"></div> -->
<!-- </div> -->

<!-- <script>
// Get the modal
var modal = document.getElementById("myModal");

// Get the image and insert it inside the modal - use its "alt" text as a caption
var img = document.getElementById("myImg");
var modalImg = document.getElementById("img01");
var captionText = document.getElementById("caption");
img.onclick = function(){
  modal.style.display = "block";
  modalImg.src = this.src;
  captionText.innerHTML = this.alt;
}

// Get the <span> element that closes the modal
var span = document.getElementsByClassName("close")[0];

// When the user clicks on <span> (x), close the modal
span.onclick = function() { 
  modal.style.display = "none";
}
</script> -->



## Coarsening Dynamics in the Cahn-Hilliard Equation

{: style="text-align: justify" }
The Cahn–Hilliard equation was proposed to model the process of phase separation in binary alloys. This equation has been extended to a variety of chemical, physical, biological, and other engineering fields such as spinodal decomposition, diblock copolymer, image inpainting, multiphase fluid flows, microstructures with elastic inhomogeneity, tumor growth simulation, and topology optimization. A common feature among those physical systems is the coarsening dynamics. [[more]](../_pages/404.md)


<!-- 
<img src="{{ base_path }}/images/CH/CH1.png" alt="cahn-hilliard-1" style="width:auto;height:250px;"> &nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH2.png" alt="cahn-hilliard-2" style="width:auto;height:250px;">;&nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH3.png" alt="cahn-hilliard-3" style="width:auto;height:250px;">;&nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH4.png" alt="cahn-hilliard-4" style="width:auto;height:250px;"> -->

<img src="{{ base_path }}/images/CH/full.png" alt="CH-full" style="width:100%;height:auto;">



## Nonlinear dynamical systems

{: style="text-align: justify" }
The Lorenz attractor. [[more]](../_pages/404.md)


<!-- 
<img src="{{ base_path }}/images/CH/CH1.png" alt="cahn-hilliard-1" style="width:auto;height:250px;"> &nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH2.png" alt="cahn-hilliard-2" style="width:auto;height:250px;">;&nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH3.png" alt="cahn-hilliard-3" style="width:auto;height:250px;">;&nbsp;&nbsp; -->
<!-- <img src="{{ base_path }}/images/CH/CH4.png" alt="cahn-hilliard-4" style="width:auto;height:250px;"> -->

<img src="{{ base_path }}/images/lorenz.gif" alt="Lorenz-full" style="width:50%;height:auto;">






<!-- {% include base_path %} -->

<!-- Research
====== -->
<!-- * M.S. in Mechanical Engineering<br>
  PPGEM, Rio de Janeiro State University (UERJ), Brazil, 2020 (expected)<br>
  Advisors: [José Pontes](http://www.gesar.uerj.br/en/staff/professor-jose-pontes.html), 
  [Norberto Mangiavacchi](http://www.gesar.uerj.br/en/staff/professor-norberto-mangiavacchi.html)
* B.S. in Mechanical Engineering<br>
  PPGEM, Rio de Janeiro State University (UERJ), Brazil, 2019<br>
  Advisors: [José Pontes](http://www.gesar.uerj.br/en/staff/professor-jose-pontes.html) -->

<!-- Honors & Awards
======
* Summer 2015: Research Assistant
  * Github University
  * Duties included: Tagging issues
  * Supervisor: Professor Git

* Fall 2015: Research Assistant
  * Github University
  * Duties included: Merging pull requests
  * Supervisor: Professor Hub -->
  
<!-- Skills
======
* Skill 1
* Skill 2
  * Sub-skill 2.1
  * Sub-skill 2.2
  * Sub-skill 2.3
* Skill 3

Publications
======
  <ul>{% for post in site.publications %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks %}
    {% include archive-single-talk-cv.html %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Service and leadership
======
* Currently signed in to 43 different slack teams -->
