---
lang: fr
title: "Lorraine Fab Living Lab (LF2L®)"
layout: splash
permalink: /fr/
locale: fr-FR


header:
  image: /assets/images/1-home/banner/banner04.jpg

intro: 
  - excerpt: "Le Lorraine Fab Living Lab® (LF2L®) permet d’accompagner la création et l’obtention de résultats immédiats grâce à un processus établi basé sur le paradigme de l’usage. En réunissant en un même espace des outils de pointe complémentaires, le LF2L® facilite le travail de réflexion collaborative et de développement de l’innovation. L’originalité du LF2L® est de pouvoir accueillir, accompagner, associer différentes communautés (citoyens utilisateurs, entrepreneurs, chercheurs, etc.) via un dispositif scientifique et technique capable d’accélérer le passage de l’idée ou concept abstrait (2D) à leur matérialisation (3D virtuelle ou prototypée) en les évaluant (4D – scénarios d’évolution)"

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
  alt="this is a placeholder image" 
  caption="Materialize" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/icon-associer.png" 
  class= "icons"  
  alt="LF2L" 
  caption="Associate" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/icon-innover.png" 
  class= "icons"  
  alt="Etudiants" 
  caption="Innovate" %}
</div>

## Entrez dans la 4ème dimension de l'Innovation
{: .text-center}

{% include feature_row id="intro" type="center" %}


<div class="community">
{% include figure 
  image_path="/assets/images/1-home/presentation/Entreprises.png" 
  class= "icons-community"  
  alt="this is a placeholder image" 
  caption="Entreprises" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Makers.png" 
  class= "icons-community"  
  alt="Makers" 
  caption="Makers" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Etudiants.png" 
  class= "icons-community"  
  alt="Etudiants" 
  caption="Etudiants" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Universitaires.png" 
  class= "icons-community"  
  alt="Universitaires" 
  caption="Universities" %}
{% include figure 
  image_path="/assets/images/1-home/presentation/Institutions.png" 
  class= "icons-community"  
  alt="Collectivities" 
  caption="Collectivities" %}
</div>



## News
{: .text-center}

{% assign posts = site.posts | where: "lang", "fr"  %}

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

        <div class="archive__item-body {{f.title_class | default: "notice--info" }}">
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
              {{ f.post_description | markdownify }}
            </div>
          {% endif %}

          {% if f.url %}
            <p style="margin-top: 10px; text-align: right;">
              <a href="{{ f_url }}" class="btn btn--success {{ f.btn_class }}">
                {{ f.btn_label | default: site.data.ui-text[site.locale].more_label | default: "Learn More" }}
              </a>
            </p>
            
          {% endif %}
        </div>
      </div>
    </div>
  {% endfor %}

</div>

See our complete
[News]({{ site.url }}/fr/news/ "Give me an click, world"){: .btn .btn--primary }
{: .text-right}


















