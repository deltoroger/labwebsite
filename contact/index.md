---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We are located in Cuernavaca, _The City of Eternal Spring_, at UNAM's Morelos campus, just 80 km from Mexico City. Our laboratory is based at the <a href="https://www.ibt.unam.mx/" target="_blank" rel="noopener noreferrer">Institute of Biotechnology (IBt)</a>, <a href="https://www.unam.mx/" target="_blank" rel="noopener noreferrer">National Autonomous University of Mexico (UNAM)</a>.

{%
  include button.html
  type="email"
  text="gerardo.deltoro [] ibt unam mx"
  link="jane@smith.com"
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://www.google.com/maps](https://maps.app.goo.gl/skxEBHcLerrq1tdX7"
%}

{% include section.html %}

{% capture col1 %}

<a href="{{ '/about-ibt/' | relative_url }}">
  <img src="{{ '/images/contact/ibt1.jpg' | relative_url }}"
       alt="Institute of Biotechnology, UNAM"
       style="width:100%; border-radius:8px;">
  <p style="text-align:center;">
    <strong>Discover the IBt</strong>
  </p>
</a>

Learn more about the history of the Institute of Biotechnology and its research community.

{% endcapture %}

{% capture col2 %}

<a href="{{ '/living-in-cuernavaca/' | relative_url }}">
  <img src="{{ '/images/contact/ibt2.jpg' | relative_url }}"
       alt="Cuernavaca, Morelos"
       style="width:100%; border-radius:8px;">
  <p style="text-align:center;">
    <strong>Living in Cuernavaca</strong>
  </p>
</a>

Discover what makes the City of Eternal Spring a special place to live and work.

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

