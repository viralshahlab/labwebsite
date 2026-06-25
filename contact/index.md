---
title: Contact
nav:
  order: 6
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

{% capture text %}

We are located on the 10th floor of the Smilow Center for Translational Research. 

{% endcapture %}

{%
  include button.html
  type="email"
  text="viralshahlab@gmail.com"
  link="viralshahlab@gmail.com"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/Fyk7uERUENoR2eFX9"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/photo.jpg"
  caption="Location"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/smilow.jpg"
  caption="Location"
%}

{% endcapture %}
