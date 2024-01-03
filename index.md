---
lang: en
title: "Lorraine Fab Living Lab"
layout: splash
permalink: /

intro:
  - image_path: /assets/images/1-home/Figure-3.jpg
    alt: "Lorraine Fab Living Lab"
    title: "Inside of the fourth dimension of Innovation"
    excerpt: "The **Lorraine Fab Living Lab® (LF2L®)** is the pedagogical support of the [ENSGSI School](https://ensgsi.univ-lorraine.fr/) and the research platform of the [ERPI Laboratory](https://erpi.univ-lorraine.fr/) dedicated to the prospective assessment of innovative usages. It supports the creation and achievement of results through an established process based on the usage paradigm  bringing together in the same space complementary advanced tools.  The originality of the LF2L® is to be able to welcome, support and associate different communities (citizen users, entrepreneurs, researchers, etc.) using a conceptual  framework of LF2L taking into consideration the 2D (concept), 3D (object), 4D (evolution scenarios) approaches involving the different type of stakeholders in order to have a foresight usage evaluation of a new concept, technology or project. This approach is useful to accelerate the deployment of industrial or urban demonstrators.
    "
    #url: "#test-link"
    #btn_label: "Read More"
    #btn_class: "btn--inverse"

founders:
  - image_path: "/assets/images/logos/ERPI.svg"
    excerpt: "[ERPI Laboratory](https://erpi.univ-lorraine.fr/)"    
  - image_path: "/assets/images/logos/ENSGSI.png"    
    excerpt: "[ENSGSI](https://www.ensgsi.univ-lorraine.fr/)"



---

![Lorrain Fab Living Lab](/assets/images/1-home/presentation/Logo-LF2L.jpg){: .align-center}

{% include feature_row id="intro" type="left"%}


{% comment %}

<center><a href="https://erpi.univ-lorraine.fr/"><img src="/assets/images/2-concept/partners-chartes/ERPI.jpg" height="250" width="250" title="ERPI Laboratory" alt="Logo ERPI"></a>
<a href="https://www.ensgsi.univ-lorraine.fr/"><img src="/assets/images/logos/ENSGSI.png" height="250" width="250" title="ENSGSI" alt="Logo ENSGSI"></a></center>







## News
{: .text-center}

{% assign posts = site.posts | where: "lang", "en"  %}

<div class="feature__wrapper">

{% for f in posts offset: 0 limit: 3 %}


<!-- * {{ f.date  | date: "%B %-d, %Y" }}: [{{f.title}}]({{f.url}}) -->

    {% if f.url contains "://" %}
      {% capture f_url %}{{ f.url }}{% endcapture %}
    {% else %}
      {% capture f_url %}{{ f.url | relative_url }}{% endcapture %}
    {% endif %}

    <div class="feature__item">
      <div class="archive__item">
        {% if f.post_teaser %}
          <div class="archive__item-teaser {{f.teaser_class}}">
            <a href="{{ f_url }}">
              <img src=
                {% if f.post_teaser contains "://" %}
                  "{{ f.post_teaser }}"
                {% else %}
                  "{{ f.post_teaser | relative_url }}"
                {% endif %}
              alt="{% if f.alt %}{{ f.alt }}{% endif %}">
            </a>

            {% if f.image_caption %}
              <span class="archive__item-caption">{{ f.image_caption | markdownify | remove: "<p>" | remove: "</p>" }}</span>
            {% endif %}
          </div>
        {% endif %}

        <div class="archive__item-body {{f.title_class | default: "notice" }}">
          {% if f.title %}
            <a href="{{ f_url }}">
              <h2 class="archive__item-title">{{ f.title }}</h2>
            </a>            
          {% endif %}

          <p class="small">
          {{ f.date  | date: "%B %-d, %Y" }}
          </p>

          {% if f.post_description %}
            <div class="archive__item-excerpt">
              {{ f.post_description | markdownify  }}
            </div>
          {% endif %}

          {% if f.url %}
            <p style="margin-top: 10px; text-align: right;">
              <a href="{{ f_url }}">
                {{ f.btn_label |  default: "Learn More" }}
              </a>
            </p>

          {% endif %}
        </div>
      </div>
    </div>
  {% endfor %}

</div>

See our complete
[News]({{ site.url }}/news/ "Give me an click, world"){: .btn .btn--primary }
{: .text-right}


{% endcomment %}
