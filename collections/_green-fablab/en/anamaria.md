---
layout: slides-total
title: Green Fablab
author: Fabio
permalink: "/projects/green-fablab/anamaria-ppt/"
image-path: "/assets/images/3-projects/gf/anamaria/presentation/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
published: false
---

<section data-markdown data-separator="---">
<script type="text/template">


{% for i in (1..46) %}
---
{% assign Diapo = "Diapositive" | append:  i   | append: ".jpeg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" -->

{% endfor %}

---

  
</script>
</section>
