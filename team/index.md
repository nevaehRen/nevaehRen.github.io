---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab members come from diverse backgrounds but share a common interests in quantitative studies of pancreatic islets. We believe that interdisciplinary approaches at systems level will gain new insights on pancreatic physiology research.

{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: postdoc" %}
{% include list.html data="members" component="portrait" filters="role: phd" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi phd$)" %}

{% include section.html background="images/background_nologo.png" dark=true %}

          Welcome to join us !

{% include section.html %}

{% capture content %}

{% include figure.html image="images/team1.png" %}
{% include figure.html image="images/team2.png" %}
{% include figure.html image="images/team3.png" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
