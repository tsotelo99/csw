---
title: Center for the Southwest
layout: unm-base
homepage: true
css: homepage.css
header-image: /assets/images/banners/red-canyon.jpg
header-title: Center for the Southwest
header-height: 24rem
background-position: center 55%
section-cards:
  - title: Initiatives
    image: /assets/images/csw-images/evening-mesa-de-los-viejos_1_orig.jpg
    link: /initiatives
    description: Explore our scholarly initiatives and research projects focused on Southwest studies.
  - title: Horn Lecture Series
    image: /assets/images/csw-images/andy-young-2.jpg
    link: /horn-lecture/2026
    description: Annual lecture series featuring prominent scholars and thinkers.
  - title: News & Events
    image: /assets/images/csw-images/andy-young-3.jpg
    link: /news/
    description: Stay updated on our latest news, events, and announcements.
---

<div class="home-page-content">
  <header class="home-intro">
    <p>The Center for the Southwest is devoted to the study of the U.S. Southwest and its borderlands, linking scholars, students, and the public through scholarly initiatives, speaker series, workshops and colloquia, student mentorship, and community outreach.</p>
  </header>

  <div class="home-landscape" role="img" aria-label="Panoramic view of the Southwest">
    <img src="{{ '/assets/images/banners/banner2.png' | relative_url }}" alt="">
    <p>Research <span aria-hidden="true">·</span> Community <span aria-hidden="true">·</span> Public History</p>
  </div>

  <section class="home-events" aria-labelledby="upcoming-events-heading">
    <h2 id="upcoming-events-heading">Upcoming Events</h2>
    <article class="featured-event">
      <div class="featured-event-flyer">
      <img src="{{ '/assets/images/fliers/dr-hooton.png' | relative_url }}" alt="Flyer for Dr. Laura Hooton's talk about Little Liberia: A Dream of Black Freedom in the US-Mexico Borderlands">
      </div>
      <div class="featured-event-copy">
        <p class="home-eyebrow">Featured Event</p>
        <h3>Book Talk: <em>Little Liberia</em></h3>
        <p class="featured-event-date"><time datetime="2026-11-17">Tuesday, November 17, 2026</time></p>
        <p class="featured-event-location">2:00 pm · History Department Common Room, Mesa Vista Hall 1104</p>
        <p>On Tuesday, November 17, we are pleased to host Dr. Laura Hooton for a talk on her most recent book, <em>Little Liberia: A Dream of Black Freedom in the US-Mexico Borderlands</em>.</p>
        <p>Her lecture will begin at 2:00 pm in the History Department Common Room in Mesa Vista Hall.</p>
        <p>Dr. Hooton is an assistant professor of history at New Mexico State University. She studies race, ethnicity, and identity in the United States and Latin America. Her interdisciplinary research focuses on African Americans in the U.S.-Mexico Borderlands, immigration and migration, social movements, and race and ethnicity in the American West. Dr. Hooton is especially interested in the intersection of Black studies and borderlands studies.</p>
      </div>
    </article>
  </section>

  <section class="home-section-links" aria-label="Explore the Center">
    {% include section-cards.html cards=page.section-cards %}
  </section>

  <section class="home-connect" aria-labelledby="connect-heading">
    <h2 id="connect-heading">Connect With Us</h2>
    <a href="https://www.instagram.com/cntrsw_unm">Instagram</a>
    <a href="https://www.facebook.com/centerforthesouthwest">Facebook</a>
    <a href="https://twitter.com/CntrSW">X (Twitter)</a>
    <a href="mailto:cntrsw@unm.edu">Email</a>
    <a href="https://forms.gle/wSubeL2YBqhFdzAb7">Join the CSW Mailing List</a>
  </section>
</div>
