---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Meet the Shah Lab! We have open positions for research technicians, graduate students, and postdocs. If you're interested please send [Viral](mailto:viralshahlab@gmail.com) your CV/Resume, what your interests are, and overall goals. 

{% include section.html %}

{% include list.html data="members" component="portrait" filter="name == 'Viral Shah'" %}
{% include list.html data="members" component="portrait" filter="role != 'principal-investigator'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

{% capture content %}

{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}
{% include figure.html image="images/photo.jpg" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
