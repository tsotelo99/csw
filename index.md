---
title: Center for the Southwest
layout: unm-base
header-image: /assets/images/banners/red-canyon.jpg
section_cards:
  - title: Initiatives
    image: /assets/images/csw-images/evening-mesa-de-los-viejos_1_orig.jpg
    link: /initiatives
    description: Explore our scholarly initiatives and research projects focused on Southwest studies.
  - title: Horn Lecture
    image: /assets/images/csw-images/andy-young-2.jpg
    link: /horn-lecture
    description: Annual lecture series featuring prominent scholars and thinkers.
  - title: News & Events
    image: /assets/images/csw-images/andy-young-3.jpg
    link: /news/
    description: Stay updated on our latest news, events, and announcements.
---

# Welcome to the Center for the Southwest

The Center for the Southwest is devoted to the study of the U.S. Southwest and its borderlands, linking scholars, students, and the public through scholarly initiatives, speaker series, workshops and colloquia, student mentorship, and community outreach.


{% assign section-cards = site.pages | where_exp: "page", "page.title contains 'initiatives'" | where_exp: "page", "page.title contains 'C. Ruth and Calvin P. Horn Lecture'" | where_exp: "page", "page.title contains 'news and events'" %}

{% include nav/section-cards.html cards = section-cards %}

---

## Connect With Us

Stay connected and engaged with the Center for the Southwest through our social media channels and direct contact.

- **Instagram:** [Follow us on Instagram](https://www.instagram.com/cntrsw_unm)
- **Facebook:** [Follow us on Facebook](https://www.facebook.com/centerforthesouthwest)
- **X (Twitter):** [Follow us on X](https://twitter.com/CntrSW)
- **Email:** [cntrsw@unm.edu](mailto:cntrsw@unm.edu)
- [**Join the CSW Mailing List**](https://forms.gle/wSubeL2YBqhFdzAb7)
