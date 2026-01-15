---
title: Center for the Southwest
layout: unm-base
header-image: /assets/images/banners/red-canyon.jpg
cards: 
  - title: "Initiatives"
    thumbnail: /assets/images/cards/initiatives.jpg
    summary: 
    link: "initiatives"

  - title: "C. Ruth and Calvin P. Horn Lecture"
    thumbnail: /assets/images/cards/horn.jpg
    summary: 
    link: "horn-lecture/about"
    
---

{% assign cards = page.cards %}

{% include card-grid.html 
cards = cards 
%}



# Welcome to the Center for the Southwest

The Center for the Southwest is devoted to the study of the U.S. Southwest and its borderlands, linking scholars, students, and the public through scholarly initiatives, speaker series, workshops and colloquia, student mentorship, and community outreach.

Feel free to like us on [Facebook](https://www.facebook.com/centerforthesouthwest) or follow us on [X](https://twitter.com/CntrSW). You can also contact us at [cntrsw@unm.edu](mailto:cntrsw@unm.edu).


{% assign cards = include.cards %}

{% for card in cards %}
{% if card.title and card.title != "" and card.thumbnail %}
<div class="card h-card">
  <a href="{{ site.baseurl }}{{ card.link | default: card.url }}" class="card-link">
    
    <!-- Image -->
    {% capture card_image_url %}
    {% include images/image-path.html image-path=card.thumbnail page-dir=card.dir %}
    {% endcapture %}
    {% assign card_image_url = card_image_url | strip %}
    <img src="{{ card_image_url }}" 
         class="card-img-left" 
         alt="{{ card.title }}">
    
    <!-- Content -->
    <div class="card-body">
      <h3>{{ card.title }}</h3>
      <p class="card-text">{{ card.summary | default: card.description }}</p>
      
      <!-- Display tags if they exist -->
      {% if card.tags %}
      <div class="tags mt-2">
        {% for tag in card.tags %}
        <span class="badge bg-secondary me-1">{{ tag }}</span>
        {% endfor %}
      </div>
      {% endif %}
    </div>
    
  </a>
</div>
{% endif %}
{% endfor %}