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

#### Technical skills: image/signal analysis, Deep-learning engineering, software development

## Experience

<strong>Post-doctoral researcher @ Centre Interdisciplinaire de Nanosciences de Marseille (<a href="https://www.cinam.univ-mrs.fr/cinam/">CINaM</a>) (June-July 2024)</strong>

* Software development and maintenance ([Celldetective](https://github.com/remyeltorro/celldetective))
* Development of appropriate benchmarks to test segmentation, classification and regression performance of traditional and Deep-learning models on test data
* Design of cell pair measurements. Develop a viewer and annotator for cell pairs
 
<strong>Ph.D. candidate @ Laboratoire Adhésion & Inflammation (<a href="https://labadhesioninflammation.org/">LAI</a>) and CINaM (September 2020 - April 2024)</strong>

* Development of a versatile method to study the effect of biological conditions on immune cell interactions with cancer cells or biomimetic surfaces. Single-cell resolution for mixed cell populations imaged using various optical microscopy techniques (brightfield, reflection interference, fluorescence...). Event formulation adapted to the system (death, spreading...).

  
## Projects

You will find more numerical projects on the [GitHub repository](https://github.com/remyeltorro). Here are three highlights where I collaborated directly with experimentalists, giving them keys to analyze their data. 

---

#### Celldetective ([Source code](https://github.com/remyeltorro/celldetective) | [Preprint](https://www.biorxiv.org/content/10.1101/2024.03.15.585250v1))

**Goal:** help experimentalists with low to no coding skills measure cell interactions from microscopy images with single-cell resolution

**Challenges:** mixed cell populations, high density, heterogeneous and partial fluorescence marking, imaging and experimental conditions varying regularly, important data volume (~50-150 Gb per experiment)

**Techniques:**
- traditional or Deep-learning segmentation (StarDist, Cellpose), with dataset curation and model training
- cell tracking with a Bayesian tracker (bTrack)
- event class formulation to describe the dynamic cell states. Automation with convolutional models interpreting single-cell signals (classification, regression)
- neighborhood schemes to link the single-cells of a population (e.g. cancer cells) to the single-cells of the other population (e.g. immune cells) and describe cell pairs
... and many more interesting techniques!

**Delivery:** a Python package accompanied by a complete graphical interface, forming a closed and intuitive ecosystem to correct images, segment, track & measure cells, pick up events, compute neighborhoods, plot results (survival functions, measurement distributions, collapse single-cell signals with respect to an event time)... 

Developed in close collaboration with experimentalist researches (Ph.D. students, engineer, post-doc). Software routinely used in LAI & CINaM on several projects.

![](images/celldetective-pipeline.png)
*Celldetective workflow*

---

#### Yeast cell detection ([Publication](https://pubs.rsc.org/en/Content/ArticleLanding/2024/LC/D4LC00011K))

**Goal:** measure the enrichment of non-fluorescent yeast cells from optical microscopy images (brightfield and fluorescence) delayed temporally (projection is not enough)

**Techniques:** 
1. traditional segmentation of the yeast cells from brightfield with top-hat filtering and thresholding
2. detection of fluorescent yeast cells with TrackPy (tracker)
3. linking of brightfield-detected yeast cells to fluorescent yeast cells with a co-distance matrix (closest neighbor within a critical distance)

**Delivery:** a Fiji macro for 1), a PyQt GUI to combine the measurements of 1) with 2) and perform task 3), all the way to plotting results

---

#### Traction force microscopy image registration ([Source code](https://github.com/remyeltorro/SPTAlign) | [Preprint](https://www.biorxiv.org/content/10.1101/2022.02.11.480084v1))


**Goal:** perform a subpixel registration of traction force microscopy images to be able to detect subtle bead motion due to cells pulling on gels

**Techniques:**
1. single-particle tracking data analysis to estimate the drift with respect to a reference frame (moving reference if needed)
2. apply an inverse shift in Fourier space to achieve a subpixel correction with no artefacts

**Delivery:** an easy-to-use Jupyter notebook and Python package

  
|Original TFM stack         | Drift corrected stack          |
|:-------------------------:|:------------------------------:|
| ![](images/drift.gif)     | ![](images/drift_corrected.gif)|


## Talks




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
  <col style="width:83%">
  <col style="width:17%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>

---

<p style="margin-bottom:3cm;"></p>





