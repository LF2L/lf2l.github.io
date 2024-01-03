---
lang: en
title: "Accelerated projects at LF2L"
layout: splash
permalink: /projects/
collection: projects
entries_layout: grid
#classes: wide

excerpt: "Projects by ERPI, ENSGSI and their partners accelerated at LF2L"
header:
 overlay_image: "assets/images/banners/LF2L-2.jpg" 
 overlay_filter: rgba(110, 110, 112, 0.5)
 show_overlay_excerpt: true 
 image_description: "projects"
#  
#date: 2018-09-07
feature_row:
  - image_path: /assets/images/3-projects/fabmanager.png
    alt: "placeholder image 2"
    title: "Fab-manager of the Lorraine Fab Living Lab"
    excerpt: "At Lorraine Fab Living Lab, we leverage the Fab Manager platform—an open-source software—to meticulously document and share a diverse array of projects developed by our students. This innovative approach allows our students to learn by doing, engaging in hands-on experiences that span from crafting prototypes to designing intermediary objects and conducting usability tests. Through this comprehensive methodology, we validate prospective solutions and empower our students to excel in practical, real-world scenarios."
    url: "https://fabmanager.lf2l.fr/#!/"
    btn_label: "Check the projects"
    btn_class: "btn--inverse"
---

# Pedagogical projects at Fab-Manager

{% include feature_row type="left" %}



# Transversal thematics


<div class="entries-{{ page.entries_layout }}">
  {% include documents-collection.html collection=page.collection sort_by=page.sort_by sort_order=page.sort_order type=page.entries_layout %}
</div>



