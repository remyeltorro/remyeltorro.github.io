---
permalink: /
title: "Hello there, I'm Rémy, PhD student"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

This is my academic website, you'll find my resume and lists of stuffs.

Publications
------
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
