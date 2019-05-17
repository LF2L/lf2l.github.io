---
layout: slides-total
title: "Users Needs v.20"
author: Fabio
permalink: "/projects/userneeds/"
image-path: "/assets/images/3-projects/User-Needs/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
---

<section data-markdown data-separator="---">
<script type="text/template">


{% for i in (1..17) %}
---
{% assign Diapo =   i   | append: ".jpg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" -->


{% endfor %}

---

  
</script>
</section>
