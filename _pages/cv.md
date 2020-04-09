---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---
<html>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
.collapsible {
  background-color: #777;
  color: white;
  cursor: pointer;
  padding: 18px;
  width: 100%;
  border: none;
  text-align: left;
  outline: none;
  font-size: 15px;
}

.active, .collapsible:hover {
  background-color: #555;
}

.collapsible:after {
  content: '\002B';
  color: white;
  font-weight: bold;
  float: right;
  margin-left: 5px;
}

.active:after {
  content: "\2212";
}

.content {
  padding: 0 18px;
  max-height: 0;
  overflow: hidden;
  transition: max-height 0.2s ease-out;
  background-color: #f1f1f1;
}
</style>
</head>
<body>

A pdf copy of my <b>Curriculum Vitae</b> can be downloaded  <u><a href="http://Fildelc.github.io/files/FilippoDelcarro_CV.pdf">here</a>.</u>
<br>
<button type="button" class="collapsible"><h2>Education</h2></button>
<div class="content">
<ul>
<li> <b>Ph.D. in Theoretical Physics</b>, Pavia University, <i>2019</i> </li>
<li> <b>M.S. in Scienze Fisiche</b> (experimental physics) 110/110, Pavia University, <i>2015</i> </li>
<li> <b>B.S. in Fisica</b>, Pavia University, <i>2013</i> </li>
</ul>
</div>

<button type="button" class="collapsible"><h2>Computing Skills</h2></button>
<div class="content">
<ul>
  <li> Programming Languages
    <ul>
      <li> Fortran </li>
      <li> Python </li>
      <li> C++ </li>
      <li> Bash </li>
    </ul>
  </li>  
  <li>Analytical software
    <ul>
      <li>Mathematica</li>
      <li>ROOT</li>
    </ul>
  </li>
  <li>Other
    <ul>
      <li>Latex</li>
      <li>vim</li>
      <li>git</li>
      <li>Office</li>
    </ul>
  </li>
</ul>
</div>


<button type="button" class="collapsible"><h2>Teaching</h2></button>
<div class="content">
<ul>
<i> Teaching Assistant, <b>Physics for Medical Students</b>, University of Pavia, <i>2015-2018</i></i>
</ul>
</div>

<button type="button" class="collapsible"><h2>Visiting</h2></button>
<div class="content">
<ul>
<li>Research Collaboration with <b>Nikhef</b> (Amsterdam, NL), hosted by Prof. Piet Mulders</li>
</ul>
</div>

<button type="button" class="collapsible"><h2>Summer Schools</h2></button>
<div class="content">
 <ul>
<li> CFNS Summer School on the Physics of the Electron Ion Collider (EIC) - Stony Brook, <i>August 2019</i> </li>
<li> <b>HUGS</b>  - Hampton University Graduate Studies Program XXXI- Jefferson Lab, <i>June 2016</i> </li>
 </ul>
</div>

<button type="button" class="collapsible"><h2>Talks</h2></button>
<div class="content">
{% for post in site.talks %}
  {% include archive-single-talk-cv.html %}
{% endfor %}
</div>  

<button type="button" class="collapsible"><h2>Publications</h2></button>
<div class="content">
{% for post in site.publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</div>

<script>
var coll = document.getElementsByClassName("collapsible");
var i;

for (i = 0; i < coll.length; i++) {
  coll[i].addEventListener("click", function() {
    this.classList.toggle("active");
    var content = this.nextElementSibling;
    if (content.style.maxHeight){
      content.style.maxHeight = null;
    } else {
      content.style.maxHeight = content.scrollHeight + "px";
    }
  });
}
</script>
<!--
</body>
</html>

  <html>
  <head>
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <style>
  .collapsible {
    background-color: #777;
    color: white;
    cursor: pointer;
    padding: 18px;
    width: 100%;
    border: none;
    text-align: left;
    outline: none;
    font-size: 15px;
  }

  .active, .collapsible:hover {
    background-color: #555;
  }

  .content {
    padding: 0 18px;
    display: none;
    overflow: hidden;
    background-color: #f1f1f1;
  }
  </style>
  </head>
  <body>



  {% include base_path %}

  A pdf copy of my CV can be downloaded  <u><a href="http://Fildelc.github.io/files/FilippoDelcarro_CV.pdf">here</a>.</u>

  <h2>Education</h2>
  <ul>
  <li> <b>Ph.D. in Theoretical Physics</b>, Pavia University, <i>2019</i> </li>
  <li> <b>M.S. in Scienze Fisiche</b> (experimental physics) 110/110, Pavia University, <i>2015</i> </li>
  <li> <b>B.S. in Fisica</b>, Pavia University, <i>2013</i> </li>
  </ul>

  <h2>Computing Skills</h2>
  <ul>
    <li> Programming Languages </li>
    <ul>
    <li> Fortran </li>
    <li> Python </li>
    <li> C++ </li>
    <li> Bash </li>
    </ul>  
    <li>Analytical software</li>
    <ul>
    <li>Mathematica</li>
    <li>ROOT</li>
    </ul>
    <li>Other</li>
    <ul>
    <li>Latex</li>
    <li>vim</li>
    <li>git</li>
    <li>Office</li>
    </ul>
  </ul>



  <script>
  var coll = document.getElementsByClassName("collapsible");
  var i;

  for (i = 0; i < coll.length; i++) {
    coll[i].addEventListener("click", function() {
      this.classList.toggle("active");
      var content = this.nextElementSibling;
      if (content.style.maxHeight){
        content.style.maxHeight = null;
      } else {
        content.style.maxHeight = content.scrollHeight + "px";
      }
    });
  }
  </script> -->
