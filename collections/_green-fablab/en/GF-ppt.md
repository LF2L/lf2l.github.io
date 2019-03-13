---
layout: slides-total
title: Green Fablab
author: Fabio
permalink: "/projects/green-fablab/PPT/"
image-path: "/assets/images/3-projects/gf/presentation/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
---

<section data-markdown data-separator="---">
<script type="text/template">

<img width="80%" class="plain" src="{{ site.baseurl | append:page.image-path | append: '../Logo-GF.png' }}">

##### Towards a distributed and local plastic recycling for OS 3D printing

**Fabio A. Cruz Sanchez**

Équipe de Recherche sur les Processus Innovatifs (ERPI)

<img height="50px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'logos/UL-LF2L.png' }}">
<img height="50px" class="plain" src="{{ site.baseurl | append:page.image-path | append: 'logos/ERPI.png' }}">

---

<!-- .slide: style="color:white; text-align: left;"  data-background="{{ site.baseurl | append:page.image-path | append: 'Introduction/BG-Plastic.jpg' }}" -->


<h3 style="color: white; text-align: left;">The Challengue: <br> Reduction of Landfill</h3>	

<img height="300px" class="plain" 
src="{{ site.baseurl | append:page.image-path | append: 'Introduction/End-of-Life-Plastics.png' }}">
Source: Plastics Europe

- Production Production (2015):
  - World: 322 Mt/year
  - Europe: 58 Mt/year (18.5%)
- Plastic Wastes (2015): 25.8 million tonnes

Plastics waste is a key resource towards **circular economy**


---

<!-- .slide: style="font-size: 25px" -->
	
<div style="width: 30%; float: left;">
	<p>17 Goals to transform our world</p>
	<em>Goal 12: Ensuring sustainable consumption and production patters</em>
	
	<img width="90%" class="plain"  
	src="{{ site.baseurl | append:page.image-path | append: 'Introduction/UN/SD-Goals.png' }}">

	<img width="90%" class="plain"  
	src="{{ site.baseurl | append:page.image-path | append: 'Introduction/EU-Circular-Economy.png' }}">

<ul>				
	<li>Paradigm change: <br> from linear economic model (<em>'take-make-dispose'</em>) to Circular <br>
	<blockquote>&#8220; The value of products and materials is maintained for as long as possible...&#8221;</blockquote>
</div>
	
<div style="float: right; width: 60%">
	<ul>
		<li>Rethinking products and services using principles based on:
		<ul class="grilla" style="font-size: 20px; width: 100%">
			<li> &#10003; durability</li>
			<li>&#10003; renewability</li>
			<li>&#10003; reuse</li>
			<li>&#10003; repair</li>
			<li>&#10003; replacement</li>
			<li>&#10003; upgrades</li>
			<li>&#10003; refurbishment</li>
			<li>&#10003; reduced material use</li>
		</ul> 
		</li>
		<br>
		<li><b>Circular Economy Action Plan</b>
			<ul>
				<li>Production</li>
				<li>Consumption</li>
				<li>Waste management</li>
				<li>From waste to resources</li>													
				<li><b style="color: green">Strategy for Plastics</b><br>
					<ul>
						<li><em>Secondary raw materials</em></li>
						<li>Quality standards for Second raw materials?</li>
						<li>Clarification of "Waste"..</li>
						<li>Legislation..</li>
					</ul>

				</li>
			</ul>
		</li>
	</ul>
<p>Plastics waste is a key resource towards <b>circular economy</b></p>
</div>



---
<!-- .slide: style="color:white; text-align: left; "  data-background="{{ site.baseurl | append:page.image-path | append: 'Introduction/3DP.jpg' }}" -->

<h3 style="color: white; text-align: left;">The Opportunity: Open Source Additive Manufacturing (3D Printing)?</h3>	

A process of joining materials to make objects from 3D model data, usually layer upon layer, as opposed to subtractive manufacturing methodologies.

-   ✓ Geometry Freedom
-   ✓ Customization a reduced cost
-   ✓ Digital Fabrication (reduced human interaction in the fabrication)
-   ✓ Material efficiency
-   ✗ Fabrication speed
-   ✗ Materials availability
-   ✗ Standards


---

### Fused Deposition Modeling (FDM)

<img width="30%" class="plain"  
	src="{{ site.baseurl | append:page.image-path | append: 'Introduction/UN/SD-Goals.png' }}">

<table style="width:60%; float: right; font-size: 25px">
	<tr>
		<th></th>
		<th>Commercial</th> 
		<th>Open Source</th>
	</tr>
	<tr>
		<td>Principle</td>
		<td>CAD + GCode + Printing</td> 
		<td>CAD + GCode + Printing</td>
	</tr>
	<tr>
		<td>Cost</td>
		<td>Expensive (5.000&#8364; - 800&#8364;K)</td> 
		<td>Low-cost (Under $5000)</td>
	</tr>
	<tr>
		<td>Methodology</td>
		<td>Closed Design (Patented)</td> 
		<td>Open design</td>
	</tr>

	<tr>
		<td>Printer</td>
		<td>Standardized</td> 
		<td>Personalized</td>
	</tr>
	<tr>
		<td>Quality:</td>
		<td>Assured by company.</td> 
		<td style="color: red">Complex?</td>
	</tr>

</table>

---

<div class="container">

<div class="col">
<img width="50%" class="plain"  
	src="{{ site.baseurl | append:page.image-path | append: 'Introduction/UN/SD-Goals.png' }}">
</div>

<div class="col">

<table style="width:40%; float: right; font-size: 25px">
	<tr>
		<th></th>
		<th>Commercial</th> 
		<th>Open Source</th>
	</tr>
	<tr>
		<td>Principle</td>
		<td>CAD + GCode + Printing</td> 
		<td>CAD + GCode + Printing</td>
	</tr>
	<tr>
		<td>Cost</td>
		<td>Expensive (5.000&#8364; - 800&#8364;K)</td> 
		<td>Low-cost (Under $5000)</td>
	</tr>
	<tr>
		<td>Methodology</td>
		<td>Closed Design (Patented)</td> 
		<td>Open design</td>
	</tr>

	<tr>
		<td>Printer</td>
		<td>Standardized</td> 
		<td>Personalized</td>
	</tr>
	<tr>
		<td>Quality:</td>
		<td>Assured by company.</td> 
		<td style="color: red">Complex?</td>
	</tr>

</table>
</div>

</div>

---


  
</script>
</section>
