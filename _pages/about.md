---
permalink: /
title: ""
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

# Data scientist

#### Technical skills: image/signal analysis, Deep-learning engineering

## Experience

<strong>Post-doctoral researcher @ Centre Interdisciplinaire de Nanosciences de Marseille (<a href="https://www.cinam.univ-mrs.fr/cinam/">CINaM</a>) (June-July 2024)</strong>

* Software development and maintenance ([Celldetective](https://github.com/remyeltorro/celldetective))
* Development of appropriate benchmarks to test segmentation, classification and regression performance of traditional and Deep-learning models on test data
* Design of cell pair measurements. Develop a viewer and annotator for cell pairs
 
<strong>Ph.D. candidate @ Laboratoire Adhésion & Inflammation (<a href="https://labadhesioninflammation.org/">LAI</a>) and CINaM (September 2020 - April 2024)</strong>

* Development of a versatile method to study the effect of biological conditions on immune cell interactions with cancer cells or biomimetic surfaces. Single-cell resolution for mixed cell populations imaged using various optical microscopy techniques (brightfield, reflection interference, fluorescence...). Event formulation adapted to the system (death, spreading...).

  
## Projects

<strong>Celldetective</strong>

<strong>Yeast cell detection</strong>

<strong>Traction force microscopy image registration</strong>


## Education


* Ph.D. Biophysics, Aix-Marseille Université, France (April 2024)

---

* M.S. Physics, Aix-Marseille Université, France (June 2020)

---

* B.S. Physics, University of Calgary, Canada / Aix-Marseille Université, France (May 2018)

---

## Publications

<style style="text/css">
  	.hoverTable{
		width:100%; 
		border-collapse:collapse; 
		border: 0px;
	}
	.hoverTable td{ 
		padding:7px; border:#4e95f4 0px solid;
	}
	/* Define the default color for all the table rows */
	.hoverTable tr{
		background: #ffffff;
	}
	/* Define the hover highlight color for the table row */
    .hoverTable tr:hover {
          background-color: #f7f7f7;
    }
</style>

<table class="hoverTable">
  <col style="width:70%">
  <col style="width:30%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>
