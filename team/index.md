---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

Our lab members come from diverse backgrounds but share a common interests in quantitative studies of pancreatic islets. We apply, develop and integrate theoretical, computational and experimental methods and tools to understand the insulin and glucagon secretion, as well as blood glucose homeostasis. 


{% include section.html %}

{% include list.html data="members" component="portrait" filters="role: pi" %}
{% include list.html data="members" component="portrait" filters="role: ^(?!pi$)" %}

{% include section.html background="images/background.jpg" dark=true %}

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor
incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis
nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.

{% include section.html %}

{% capture content %}

{% include figure.html image="images/team1.png" %}
{% include figure.html image="images/team2.png" %}
{% include figure.html image="images/team3.png" %}

{% endcapture %}

{% include grid.html style="square" content=content %}
