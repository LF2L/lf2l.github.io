---
title: "Project: Open Source Melt Flow index"
class: wide
date: 2020-12-04
permalink: /projects/green-fablab/osmfi/
image-path: "/assets/images/3-projects/gf/stages/osmfi/"

excerpt: "Towards a circular economy for 3D printing technology"
header:
  teaser: "/assets/images/3-projects/gf/teaser.jpg"
  overlay_image: "/assets/images/3-projects/gf/teaser-2.jpg"
  overlay_filter: 0.5

toc: true
toc_label: "Project Development"
toc_icon: "file-alt"
toc_sticky: true


Planning:
  - title: "Global project"
    url: /projects/green-fablab/osmfi/

  - title: "November"
    url: /green-fablab/osmfi/
  - title: "December"
    url: /green-fablab/osmfi/


partners:
- image_path: "/assets/images/3-projects/gf/logos/MTU.png"
  teaser_class: GF-partners
  alt: MTU
  title: ''
  excerpt: "[Michigan Technological University](https://www.mtu.edu)"  

---

## Proposition of Internship

The Green Fablab project is based on our recent article of Distributed Recycling via additive Manufacturing (DRAM) approach
The context of this internship project is placed in the **Quality (V)** phase.

![Lorraine Fab Living Lab](/assets/images/3-projects/gf/DRAM.png)
[See our paper in this link](/green-fablab/review-recycling/)

Taking into account the sustainability notion which is a currently  major societal issue, the FabLab concept goes towards a better use the resources present in these spaces.

We have developed various works on technical and logistical point of view to recycle plastic inside the LF2L.

However, One key point is missing. *How can we evaluate the 'usefulness' of plastic waste material to be recycled via DRAM approach'*.
This is a major technical aspect in order to understand the characteristics of the recycled materials.

### Open Source Melt flow Index

<img width="40%" class="align-left" src="{{ site.baseurl | append:page.image-path | append: 'MFI.jpg' }}">
Rheological properties are one of the most important parameters in the quality assessment of the polymer materials. Viscosity and fluidity of the material are related to the polymer's molecular structure, which is
correlated to the process parameters to take into account in the injection or printing process . Therefore, the final quality of the fabricated object (e.g. resistance, surface finish, dimensional
accuracy) are related to the initial state of the material. **Melt Flow Index** is one of the rheological properties to measure with the purpose to qualify the recycled material is for 3D printing process.

Melt Flow Index (MFI) is an indirect technique to measure the viscosity of polymers, which is also correlated with the and the molecular weight of a polymer. It is used in polymer technology as a product specification since this value gives an indication of the processing properties of the polymer. The polymer is heated in a small oven and a normal load is applied to the molten material. The melted material is extruded through an orifice and the weight of the extruded material over a 10-min period is recorded as the melt index (MI) value. The value of MFI is expressed as the mass of polymer melt pushed from the heated cylinder of the extrusion plastometer through its precision bore orifice by its piston in a period of time, the standard units of the value being grams per ten minutes (g/10 min). The weight used was 2.16 Kg and the temperature was 180.

Of all the family of capillary flow systems the Melt Flow Indexer is the cheapest and the most widely used. This test can be repeated at two different loads to determine the flow rate ratio (FRR). Flow rate may be determined as a function of applied load so that a qualitative indication of pseudoplasticity is readily obtained by comparing the ratios of flow rate at two different loads. The MI and FRR values provide correlations to the molecular weight and molecular weight distribution. Assuming all other things are equal, the lower the MI values, the higher the molecular weight and the higher the FRR, and the broader the molecular weight distribution.

This projects is in collaboration with MTU

<div id="GF-partners">  
{% include feature_row id="partners" %}
</div>



## Goal

The main goal of the project is **to design, built and test an open hardware melt flow index system for the LF2L conditions**.
Moreover, to establish the quality and reproducibility of the test process with respect to the commercial test machines.


### Specific goals

The main specific goals of this internship are:

-   Mechanical Design process considering the technical and user requirements
-   Fabrication considering the resources of a innovation space such as FabLabs
-   Realization of first trials test using virgin material (e.g. PLA) for calibration purposes.
-   Calibration test with regard to the commercial machines
-   Documentation of the prototype.
-   Establishment a protocol to use considering the user experience.

### Expected elements to the end of the project

The following elements are expected as results:

1.  Benchmarking of the available open source testing machines taking to account the time, expertise, difficulty to maintain and cost.
2.  Development of technical features to consider.
3.  CAD models with the final version of the prototypes
4.  An on-line platform (e.g. a wiki, html page) for a complete documentation
5.  Bill of Materials (BOM)
6.  CAD model

## Timming: February 2021 - Sept 2021

## Contact
First, read our [Internship guide](/green-fablab/internships/).
Then, send us your CV and cover letter. If additional questions, let us know

- Alaa Hassan (Alaa.Hassan{at}univ-lorraine.fr)
- Hakim Boudaoud (Hakim.Boudaoud{at}univ-lorraine.fr)
