---
permalink: /
title: "Data scientist"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Technical skills: image/signal analysis, Deep-learning engineering

## Relevant experience

**Post-doctoral researcher @ Centre Interdisciplinaire de Nanosciences de Marseille (CINaM) (June-July 2024)**

* Software development and maintenance ([Celldetective](https://github.com/remyeltorro/celldetective))
* Develop appropriate benchmarks to test segmentation, classification and regression performance of traditional and Deep-learning models on test data
* Design cell pair measurements. Develop a viewer and annotator for cell pairs
 
**Ph.D. candidate @ Laboratoire Adhésion & Inflammation (LAI) and CINaM (September 2020 - April 2024)**

* Developed a versatile method to study the effect of drug treatments on immune cell interactions with cancer cells or biomimetic surfaces. Single-cell resolution for mixed cell populations imaged using various optical microscopy techniques (brightfield, reflection interference, fluorescence...). Event formulation adapted to the system (death, spreading...).

  
## Projects

**Celldetective**

**Yeast cell detection**

**Traction force microscopy image registration**


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
