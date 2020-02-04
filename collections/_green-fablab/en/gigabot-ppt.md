---
layout: slides-total
title: Green Fablab
author: Fabio
permalink: "/green-fablab/re3d-meeting/"
image-path: "/assets/images/3-projects/gf/gigabot/meeting/"
description: Presentation of Green Fablab of the University of Lorraine
theme: white
transition: slide
published: false

width: "80%"
height: "80%"

---

<section data-markdown data-separator="---">
<script type="text/template">


{% for i in (1..9) %}

{% assign Diapo = "Diapositive" | append:  i   | append: ".jpeg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" data-background-size="80%"  -->

---

{% endfor %}


{% for i in (10..40) %}

{% assign Diapo = "Diapositive" | append:  i   | append: ".jpeg"  %}

<!-- .slide: data-background="{{ site.baseurl | append:page.image-path | append: Diapo  }}" data-background-size="80%"  -->

---

{% endfor %}



  
</script>
</section>
