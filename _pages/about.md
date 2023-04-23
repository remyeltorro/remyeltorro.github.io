---
permalink: /
title: "Welcome to the personnal page of Lama Awada, PhD student"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

My name is Lama and I'm a little 💩


Publications
------
<style style="text/css">
  	.hoverTable{
		width:85%; 
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
  <col style="width:75%">
  <col style="width:25%">
  {% for post in site.publications reversed %}
    {% include archive-single-pub.html %}
  {% endfor %}
</table>
