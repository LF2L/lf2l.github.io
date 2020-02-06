---
lang: en
title: "Lorraine Fab Living Lab"
layout: splash
permalink: /

header:
  image: banner
  banner:
    id: home
    time: 20000
    images:
      - url: /assets/images/1-home/banner/banner01.jpg
      - url: /assets/images/1-home/banner/banner02.jpg
      - url: /assets/images/1-home/banner/banner03.jpg
      - url: /assets/images/1-home/banner/banner04.jpg
  
intro: 
  - excerpt: "The **Lorraine Fab Living Lab® (LF2L®)** is a research platform of the ERPI Laboratory dedicated to the prospective assessment of innovative usages. It supports the creation and achievement of results through an established process based on the usage paradigm  bringing together in the same space complementary advanced tools.  The originality of the LF2L® is to be able to welcome, support and associate different communities (citizen users, entrepreneurs, researchers, etc.) using a conceptual  framework of LF2L taking into consideration the 2D (concept), 3D (object), 4D (evolution scenarios) approaches involving the different type of stakeholders in order to have a foresight usage evaluation of a new concept, technology or project. This approach is useful to accelerate the deployment of industrial or urban demonstrators."

icons:
  - image_path: /assets/images/1-home/presentation/icon-materialiser.png
    teaser_class: icons
    title_class: icons
    alt: "Associate IDeas"
    title: "Materialise"
    excerpt: ""
  - image_path: /assets/images/1-home/presentation/icon-associer.png
    alt: "Associate IDeas"
    title: "Associate"
    excerpt: ""
    teaser_class: icons
    title_class: icons
  - image_path: /assets/images/1-home/presentation/icon-innover.png
    alt: "Innvate"
    title: "Innovate"
    excerpt: ""
    teaser_class: icons
    title_class: icons

---


![Lorrain Fab Living Lab](/assets/images/1-home/presentation/Logo-LF2L.jpg){: .align-center}


<div class="community">
{% include figure 
  image_path="/assets/images/1-home/presentation/icon-materialiser.png" 
  class= "icons"  
  alt="Materialize a LF2L" 
  caption="**Materialize**" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/icon-associer.png" 
  class= "icons"  
  alt="Associer at LF2L" 
  caption="**Associate**" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/icon-innover.png" 
  class= "icons"  
  alt="Innover at LF2L" 
  caption="**Innovate**" %}
</div>

## Inside of the fourth dimension of Innovation 
{: .text-center}

{% include feature_row id="intro" type="center" %}





## Communities 
{: .text-center}

<div class="community">
{% include figure
  image_path="/assets/images/1-home/presentation/Entreprises.png" 
  class= "icons-community"  
  alt="" 
  caption="Entreprises"
  url= "/communities/enterprises/" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Makers.png" 
  class= "icons-community"  
  alt="" 
  caption="Makers" 
  url= "/communities/makers/" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Etudiants.png" 
  class= "icons-community"  
  alt="" 
  caption="Etudiants" 
  url= "/communities/students/" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Universitaires.png" 
  class= "icons-community"  
  alt=" " 
  caption="Universities" 
  url= "/communities/enterprises/" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Institutions.png" 
  class= "icons-community"  
  alt=" " 
  caption="Collectivities" 
  url= "/communities/collectivities/" %}
</div>




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




