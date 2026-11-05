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
%}

{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/3y4QifmqZwe5qfmq6"
%}


{% include section.html %}

{% capture col1 %}

[![Institute of Biotechnology]({{ '/images/contact/ibt2.jpg' | relative_url }})]({{ '/about-ibt/' | relative_url }})

**[Discover the IBt]({{ '/about-ibt/' | relative_url }})**

Learn more about the history of the Institute of Biotechnology and its research community.

{% endcapture %}

{% capture col2 %}

[![Cuernavaca, Morelos]({{ '/images/contact/ibt2.jpg' | relative_url }})]({{ '/living-in-cuernavaca/' | relative_url }})

**[Living in Cuernavaca]({{ '/living-in-cuernavaca/' | relative_url }})**

Discover what makes the City of Eternal Spring a special place to live and work.

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

