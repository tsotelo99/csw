---
title: Center for the Southwest
layout: unm-base
homepage: true
header-image: /assets/images/banners/bartlett-arizona.jpg
header-title: Center for the Southwest
header-text: Exploring the histories, cultures, and borderlands of the U.S. Southwest through scholarship, education, and community engagement.
header-height: 24rem
background-position: center 55%
css: homepage.css
---

<div class="home-page-content">
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

  <div class="about-page">
    <section aria-labelledby="mission-title" class="about-mission" id="our-mission">
      <div class="about-mission-copy">
        <p class="about-eyebrow">Our mission</p>
        <h2 id="mission-title">Connecting People, Places<br class="desktop-break"> and Perspectives</h2>
        <p>The Southwest is home to diverse landscapes and communities, a border-crossing heritage, and cycles of imperial and national conquest and local resistance.</p>
        <p>The Center for the Southwest builds on the strengths of UNM’s History Department in U.S. West, Native American, Latin American, borderlands, gender, and environmental history to advance the study of the region in continental, hemispheric, and global contexts. It supports historical and cross-disciplinary approaches, with an eye to the transnational and trans-regional networks that make the Southwest a crossroads of empires, nations, and peoples.</p>
        <p>Through scholarly initiatives, speakers, workshops, colloquia, institutional partnerships, student mentorship, and community engagement, it connects scholars, students, and publics across the borderlands and beyond.</p>
        <a class="about-button" href="{{ site.baseurl }}/initiatives/">Explore our initiatives <span aria-hidden="true">→</span></a>
      </div>
      <img class="about-mission-image" src="{{ site.baseurl }}/assets/images/csw-images/los-fresnos-view.jpg" alt="A view of the diverse landscapes of the Southwest">
    </section>

    <section aria-labelledby="people-title" class="about-people" id="meet-our-team">
      <p class="about-eyebrow">People</p>
      <h2 id="people-title">Meet Our Team</h2>
      <div class="about-team-grid">
        {% for person in site.data.people.current-csw %}
        <article class="about-person">
          <img src="{{ site.baseurl }}/assets/images/people/{{ person.image | strip }}" alt="{{ person.name }}">
          <div class="about-person-details">
            <h3>{{ person.name }}</h3>
            <p class="about-person-title">{{ person.title }}</p>
            {% if person.office %}<p class="about-person-office">{{ person.office }}</p>{% endif %}
            {% if person.email %}<a class="about-person-link" href="mailto:{{ person.email }}">Contact {{ person.name | split: ' ' | first }} <span aria-hidden="true">→</span></a>{% endif %}
          </div>
        </article>
        {% endfor %}
      </div>
    </section>

    <section aria-labelledby="history-title" class="about-history" id="our-history">
      <p class="about-eyebrow">Our history</p>
      <h2 id="history-title">A Legacy of Scholarship and Impact</h2>
      <ol class="about-timeline">
        <li class="about-milestone">
          <span aria-hidden="true" class="about-milestone-icon"><span class="fa fa-university"></span></span>
          <h3>1989</h3>
          <p>Established as the Center for the American West under the direction of Richard W. Etulain, building on UNM’s longstanding strengths in regional history.</p>
          <details>
            <summary>More from this period</summary>
            <p>Drawing on the department’s visibility in the field of regional history and over a half-century of research, teaching, publishing, library collecting, and generous donor support, the Center hosted seminars, conferences, and workshops, sponsored the yearly Calvin P. Horn lectures (and an affiliated series on western history and culture with <a href="https://unmpress.com/Calvin_P_Horn_Lectures_on_Western_History_and_Culture">UNM Press</a>), and supported UNM's highly ranked graduate program.</p>
          </details>
        </li>
        <li class="about-milestone">
          <span aria-hidden="true" class="about-milestone-icon"><span class="fa fa-star"></span></span>
          <h3>2001</h3>
          <p>Renamed the Center for the Southwest under Virginia Scharff. The Center developed national partnerships, supported landmark scholarship, and welcomed the Horn Lecture Series.</p>
          <details>
            <summary>More from this period</summary>
            <p>The new name reflected rising faculty interest in the U.S. Southwest and its borderlands with Mexico. Scharff forged networks with centers and institutes across the nation, including the Autry National Center of the American West, the Clements Center for Southwest Studies at SMU, and Stanford’s Bill Lane Center for the American West. Symposia co-sponsored with the Clements Center generated the edited volumes <a href="https://www.ucpress.edu/book.php?isbn=9780520272392"><em>On the Borders of Love and Power</em></a> and <a href="https://www.ucpress.edu/book/9780520283794/civil-war-wests"><em>Civil War Wests: Testing the Limits of the United States</em></a>. With generous support of the Horn family, Scharff also invited nationally recognized scholars each year to engage with faculty, students, and the wider community through the C. Ruth and Calvin P. Horn Lecture Series in Western History and Culture.</p>
          </details>
        </li>
        <li class="about-milestone">
          <span aria-hidden="true" class="about-milestone-icon"><span class="fa fa-users"></span></span>
          <h3>2019</h3>
          <p>Samuel Truett assumed the directorship, expanding the Center’s border-crossing vision and collaborations with Indigenous scholars and campus partners.</p>
          <details>
            <summary>More from this period</summary>
            <p>Truett built on the Center’s regional foundations with an outward-looking vision tied to the History Department’s strengths in western U.S., Native American, and Latin American history. In 2019–20, the Center worked with the <a href="https://ifair.unm.edu/">Institute for American Indian Research</a> and the <a href="https://www.newberry.org/newberry-consortium-american-indian-studies">Newberry Consortium in American Indian Studies</a> to host <a href="{{ site.baseurl }}/about/annual-reports">visiting Indigenous scholars</a> and build graduate student networks across campus. These collaborations laid groundwork for the Center’s long-term Indigenous Borderlands and Borderland Environments initiatives.</p>
          </details>
        </li>
        <li class="about-milestone">
          <span aria-hidden="true" class="about-milestone-icon"><span class="fa fa-globe"></span></span>
          <h3>Today</h3>
          <p>We connect historians, communities, students, and publics through research initiatives, education, and community engagement across the Southwest and beyond.</p>
          <details>
            <summary>Our ongoing work</summary>
            <p>The Center’s research initiatives embrace interdisciplinary collaboration, connecting historians to other fields of inquiry and social action. Approaching the Southwest as a space of interconnected communities, the Center seeks to make the region relevant to a wide range of scholars, students, and publics.</p>
          </details>
        </li>
      </ol>
      <p class="about-history-summary">The Center’s research initiatives embrace interdisciplinary collaboration, connecting historians with other fields of inquiry and social action. We approach the region as a space of interconnected communities and make it relevant to a wide range of scholars, students, and publics.</p>
    </section>
  </div>

  <section class="home-connect" aria-labelledby="connect-heading">
    <h2 id="connect-heading">Connect With Us</h2>
    <a href="https://www.instagram.com/cntrsw_unm">Instagram</a>
    <a href="https://www.facebook.com/centerforthesouthwest">Facebook</a>
    <a href="https://twitter.com/CntrSW">X (Twitter)</a>
    <a href="mailto:cntrsw@unm.edu">Email</a>
    <a href="https://forms.gle/wSubeL2YBqhFdzAb7">Join the CSW Mailing List</a>
  </section>
</div>
