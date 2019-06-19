---
layout: slides-total
title: Green Fablab
author: Fabio
permalink: "/projects/summer-school/"
image-path: "/assets/images/summer-school/"
description: A presentation slide for how to use reveal.js in Jekyll
theme: white
transition: slide
published: true

width: "80%"
height: "80%"

---

<section data-markdown data-separator="---">
<script type="text/template">


{% for i in (1..9) %}

{% assign Diapo = "Day II - Protoyping.00" | append:  i   | append: ".jpeg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" data-background-size="80%"  -->

---

{% endfor %}


{% for i in (10..40) %}

{% assign Diapo = "Day II - Protoyping.0" | append:  i   | append: ".jpeg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" data-background-size="80%"  -->

---

{% endfor %}



  
</script>
</section>
