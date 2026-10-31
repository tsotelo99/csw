---
title: Center for the Southwest
layout: unm-base
homepage: true
css: homepage.css
header-image: /assets/images/banners/bartlett-arizona.jpg
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
---

<div class="home-page-content">
  <section class="home-intro" aria-labelledby="home-intro-title">
    <div class="home-intro-copy">
      <p class="home-eyebrow">Scholarship · Community · The Southwest</p>
      <h1 id="home-intro-title">Center for the Southwest</h1>
      <p class="home-intro-lead">Discover the histories, cultures, and connections that shape the U.S. Southwest and its borderlands.</p>
      <p class="home-intro-description">We bring scholars, students, and communities together through research initiatives, public programs, mentorship, and conversation.</p>
      <div class="home-intro-actions">
        <a class="home-action-primary" href="#explore-the-center">Explore our work <span aria-hidden="true">↓</span></a>
        <a class="home-action-secondary" href="#upcoming-events-heading">See upcoming events <span aria-hidden="true">→</span></a>
      </div>
    </div>
  </section>

  <section class="home-events" aria-labelledby="upcoming-events-heading">
    <div class="home-section-heading">
      <p class="home-eyebrow">Gather with us</p>
      <h2 id="upcoming-events-heading">Upcoming Events</h2>
      <p>Join the conversation through lectures, workshops, and community programs.</p>
    </div>
    <div class="home-feature-grid">
      <article class="featured-event">
        <div class="featured-event-flyer">
          <img src="{{ '/assets/images/fliers/dr-hooton.png' | relative_url }}" alt="Flyer for Dr. Laura Hooton's talk about Little Liberia: A Dream of Black Freedom in the US-Mexico Borderlands">
        </div>
        <div class="featured-event-copy">
          <p class="home-eyebrow">Featured Event</p>
          <h3>Book Talk: <em>Little Liberia</em></h3>
          <p class="featured-event-date"><time datetime="2026-11-17">Tuesday, November 17, 2026</time></p>
          <p class="featured-event-location">2:00 pm · History Department Common Room, Mesa Vista Hall 1104</p>
          <details>
            <summary>Event and speaker details</summary>
            <p>On Tuesday, November 17, we are pleased to host Dr. Laura Hooton for a talk on her most recent book, <em>Little Liberia: A Dream of Black Freedom in the US-Mexico Borderlands</em>.</p>
            <p>Her lecture will begin at 2:00 pm in the History Department Common Room in Mesa Vista Hall.</p>
            <p>Dr. Hooton is an assistant professor of history at New Mexico State University. She studies race, ethnicity, and identity in the United States and Latin America. Her interdisciplinary research focuses on African Americans in the U.S.-Mexico Borderlands, immigration and migration, social movements, and race and ethnicity in the American West. Dr. Hooton is especially interested in the intersection of Black studies and borderlands studies.</p>
          </details>
        </div>
      </article>
      <div class="home-side-events">
        <article class="side-event">
          <a class="side-event-flyer" href="{{ '/assets/images/fliers/dr-hooton-grad-lunch.png' | relative_url }}">
            <img src="{{ '/assets/images/fliers/dr-hooton-grad-lunch.png' | relative_url }}" alt="Graduate Student Lunch with Dr. Laura Hooton flyer">
          </a>
          <div class="side-event-copy">
            <p class="home-eyebrow">Graduate Student Lunch</p>
            <h3>Meet Dr. Laura Hooton</h3>
            <p>November 17, 2026 · 12–1 pm</p>
            <p>History Common Room, Mesa Vista Hall 1104</p>
            <a class="side-event-link" href="{{ '/assets/images/fliers/dr-hooton-grad-lunch.png' | relative_url }}">View flyer <span aria-hidden="true">→</span></a>
          </div>
        </article>
        <article class="side-event">
          <a class="side-event-flyer" href="{{ '/assets/images/fliers/2027-horn-lecture.png' | relative_url }}">
            <img src="{{ '/assets/images/fliers/2027-horn-lecture.png' | relative_url }}" alt="2027 C. Ruth and Calvin P. Horn Lecture flyer for Dr. Rachel St. John">
          </a>
          <div class="side-event-copy">
            <p class="home-eyebrow">Save the Date · Horn Lecture</p>
            <h3>Dr. Rachel St. John</h3>
            <p>March 4, 2027 · 5:30 pm</p>
            <p><em>The Imagined States of America: An Unmanifest History</em></p>
            <a class="side-event-link" href="{{ '/assets/images/fliers/2027-horn-lecture.png' | relative_url }}">View flyer <span aria-hidden="true">→</span></a>
          </div>
        </article>
      </div>
    </div>
  </section>

  <section class="home-section-links" aria-labelledby="explore-the-center">
    <div class="home-section-heading">
      <p class="home-eyebrow">Go deeper</p>
      <h2 id="explore-the-center">Explore the Center</h2>
      <p>Find the people, projects, and ideas shaping our work across the Southwest.</p>
    </div>
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
