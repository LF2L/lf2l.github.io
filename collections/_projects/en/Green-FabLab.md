---
lang: en
layout: single
classes: wide
title: Green Fablab
date: 2018-09-10 00:00:00 +0000
permalink: "/projects/green-fablab/"
image-path: "/assets/images/3-projects/gf/"
excerpt: Towards a circular economy for 3D printing technology
header:
  teaser: "/assets/images/3-projects/gf/teaser.jpg"
  overlay_image: "/assets/images/3-projects/gf/teaser-2.jpg"
  overlay_filter: 0.5
intro:
- excerpt: "**The creation of a local recycling process for open source 3D printing
    technology can open new opportunities for a circular economy**"
sidebar:
  nav: GF-articles
gallery:
- url: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-I.jpg"
  image_path: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-I.jpg"
  alt: Ma thèse en 180s Fabio Cruz
  title: Ma thèse en 180s Fabio Cruz
- url: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-II.jpg"
  image_path: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-II.jpg"
  alt: Ma thèse en 180s Fabio Cruz
  title: Ma thèse en 180s Fabio Cruz
- url: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-III.jpg"
  image_path: "/assets/images/3-projects/gf/BD/en/Fabio-MT180-II.jpg"
  alt: Ma thèse en 180s Fabio Cruz
  title: Ma thèse en 180s Fabio Cruz
projects:
- image_path: "/assets/images/3-projects/gf/articles/proj-1/thumb.png"
  alt: ''
  title: 'Towards a standard protocol for 3D printers '
  excerpt: Proposition d'un protocole standard d'expérimentation afin de caractériser
    la précision dimensionnelle d'une imprimante 3D open source.
  url: "/green-fablab/standard-protocol"
  btn_label: Plus de détails
  btn_class: btn--info
- image_path: "/assets/images/3-projects/gf/articles/proj-2/thumb.png"
  alt: ''
  title: Polymer recycling for 3D printing
  excerpt: Proposition d'une métodologie systematique pour évaluer la recyclabilité
    des thermoplastiques utilisés dans les imprimantes open source.
  url: "/green-fablab/recycling-methodology/"
  btn_label: Plus de détails
  btn_class: btn--info
- image_path: "/assets/images/3-projects/gf/articles/proj-3/thumb.png"
  title: Closed-Loop supply chain for distributed recycling process
  excerpt: a conceptual model is developed and proposed for the collection process
    in a Closed Loop Supply Chain (CLSC) network of local and distributed plastic
    recycling.
  url: "/green-fablab/logistic/"
  btn_label: Plus de détails
  btn_class: btn--info
partners:
- image_path: "/assets/images/3-projects/gf/logos/CESI.jpg"
  teaser_class: GF-partners
  alt: CESI
  title: ''
  excerpt: "[Engineering school](https://www.eicesi.fr/)"
- image_path: "/assets/images/3-projects/gf/logos/ENSGSI.jpg"
  teaser_class: GF-partners
  alt: ENSGSI
  title: ''
  excerpt: "[National School in Industrial Systems Engineering](https://www.ensgsi.univ-lorraine.fr/)"
- image_path: "/assets/images/3-projects/gf/logos/LGRP.jpg"
  teaser_class: GF-partners
  alt: LRGP
  title: ''
  excerpt: "[Laboratoire Réactions et Génie des Procédés](http://lrgp-nancy.cnrs.fr/)"

---

{% assign logo-gf={{site.baseurl|append:page.image-path|append:'Logo-GF.png'}} %}
{% include figure image_path = logo-gf 
  class='align-center'
  alt="Logo Green Fablab" %}

{% include feature_row id="intro" type="center" %}

<!-- Intro -->
The concept of **Green FabLab** is the intersection of several societal trends.
<!-- 3D Printing -->
From one side, there have been an growing interesting in the additive manufacturing technology (a.k.a 3D printing) technology.
The creation of the fantastic [RepRap Projet](https://reprap.org/), an open source project, opened up many possibilities in terms of appropiation for the 3D printing technology, doing the filament fused deposition the most used technique in the additive manufacturing world.

<!-- Innovation Spaces -->
In a parallelal way, the proliferation of innovation spaces such as Fablabs, hackerspaces, makerspaces, it is creating a meeting place for passionate people about technology and the digital tools for the local fabrication/repairing/hacking uses.

<!-- Conclusion -->
Finally, the impact of the human activity to the environment and natural resources scarcity is taking more and more place in the general conscious.
Therefore, a central issue today is how preserve material resources  to in terms of circular in order to preserve the as much as possible

> Our vision of **Green Fablab** (or Hackerspace, or Makespace) is that in these geographically distributed spaces, they can be considered not only as a _fabrication spaces_, but also a recycling, remanufacturing and refurbishing places in order to contribute to a more circular economy.

***

## Green Fablab en Images

{: #GF-Images .GF-titles }

{% include gallery
caption="Comic made in the _Ma Thèse en 180s_ from UL. [Made by PebFox](http://www.pebfox.com/blog/)" %} {: .text-right}

## Innovation Spaces

{: #inno-spaces .GF-titles }

![image-left](%7B%7Bsite.baseurl%7Cappend:page.image-path%7Cappend:'LF2L.jpg'%7D%7D){: .align-left}
There is an increasingly interest of organizations in creating dedicated environments to foster innovation processes. Depending of the context, these physical environments can take form of laboratories with different kind of spaces such as creativity and prototyping rooms, co-workings spaces, testing rooms, etc.

According to the literature an “innovation laboratory” is a room or a set of rooms designed for spatial reconfiguration, participant observation, writing spaces, materials for visualization (post-it notes, paper, pens, cards), and ICT to support brainstorming and distributed group working.

Looking for a more integral definition, an innovation laboratory can be described as: **_facilities for encouraging creative behaviors and supporting innovative projects through the provision of appropriate resources, visualization and prototyping facilities, and the ability to reconfigure new projects_**.
<br>

**For more details:** <br>
<cite>F. Osorio Bustamante, J. I. Peña Reyes, M. Camargo, and L. Dupont,</cite> --- [“Spaces to foster and sustain innovation: Towards a conceptual framework,”](https://ieeexplore.ieee.org/abstract/document/7438661) in 2015 International Conference on Engineering, Technology and Innovation (ICE), 2015.
{: .small  .notice--primary}

***

## Open Source 3D Printing

{: #OS3DP .GF-titles }

![image-left](%7B%7Bsite.baseurl%7Cappend:page.image-path%7Cappend:'3DP.jpg'%7D%7D){: .align-right}
Additive Manufacturing (AM) is the name given to all the fabrication technologies in which the working principle is the layer-by-layer material deposition, as a contrast to the more traditional subtractive manufacturing methodologies.

This basic principle drives nearly all AM machines, with some variations in terms of the techniques used for creating layers and in bonding them together.
Different synonyms have been evoked (e.g. rapid prototyping, additive fabrication, additive processes, additive techniques, additive layer manufacturing, layer manufacturing, solid freeform fabrication) throughout the development of this manufacturing process.

Thanks to the expiration of Fused Deposition Modeling (FDM) patent in the mid-2000s which it is one additive manufacturing technique, Adrian Bowyer and his team at the University of Bath worked on the concept of self-replicating machines which are able of manufacturing their own parts by themselves.


They designed in order to be simple and easy to use that anyone would be able to build them. _This was the start of the_ [_RepRap project (or Replicating Rapid-prototyper)_](https://reprap.org/wiki/RepRap) _and the open source Additive Manufacturing technology_

***

## Potential of the recycling process for 3D printing technology

{: #GF-Mission .GF-titles }

<figure style="width: 230px" class="align-left"> <img src="{{ site.baseurl | append:page.image-path | append:'Recycling.jpg'}}" alt=""> <figcaption> <a href="http://www.pebfox.com/" target="_blank">Photo by: Peb</a>. </figcaption> </figure> 

There is a great potential of Additive Manufacturing (AM) to contribute to a sustainable manufacturing. And it is reasonable to expect that AM will positively impact the societal development in the next decades to come. The development of sustainable principles, applications and practices play a key role in research activity in order to enable environmentally friendly, economically advantageous, and societal benefit-driven AM methodologies.

Energy, material consumption and environmental impacts are vital aspects that AM can better act to optimize in the manufacturing industrial context.
On the basis of these concepts, some major goals have been outlined in order to fully incorporate sustainability principles in the AM processes.

The integration of recycled material for the 3D printing technology and in the innovation spaces is a potential approach to contribute to the current sustainability issues in the world.
Plastic recycling process of the sourrounding areas (street, neighborhood) could be carried out at small lot sizes minimizing, energy consumptions, and carbon emissions compared to the tradition centralized systems.

> The purpose of the **Green Fablab** project is to study the technical and logistical feasability to use material recycling  on open source 3D printers, in order to establish a sustainable waste management option for this technology
> A _distributed polymer_ recycling process could be a new paradigme that can open new scenarios in the near future.

**For more details:** <br>
<cite>F. Osorio Bustamante, J. I. Peña Reyes, M. Camargo, and L. Dupont,</cite> --- [“Spaces to foster and sustain innovation: Towards a conceptual framework,”](https://ieeexplore.ieee.org/abstract/document/7438661) in 2015 International Conference on Engineering, Technology and Innovation (ICE), 2015.
{: .small  .notice--info}

***

## Our research

{: #GF-research .GF-titles }

<div id="GF-projects">
{% include feature_row id="projects" %}
</div>

***

## Nos Etudiants

{: #GF-students .GF-titles }

{% assign carousel = site.data.Green-Fablab.Equipe-en %}
{% include carousel  %}

## Nos partenaires

{: #GF-partners .GF-titles }

<div id="GF-partners">
{% include feature_row id="partners" %}
</div>