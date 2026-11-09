---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our goal is to conduct research to the highest scientific standards while contributing to the training and development of the next generation of scientists. We are committed to mentoring our students and fostering an inclusive, collaborative environment that values diversity of backgrounds, perspectives, and ideas.

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}
