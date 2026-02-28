---
title: Team
nav:
  order: 3
  tooltip: About our team
---

# {% include icon.html icon="fa-solid fa-users" %}Team

{% include section.html %}

{% include list.html data="members" component="portrait" filter="role == 'pi'" %}
{% include list.html data="members" component="portrait" filter="role != 'pi'" %}

{% include section.html background="images/background.jpg" dark=true %}

{% include section.html %}

# {% include icon.html icon="fa-solid fa-users" %}Alumni

<!-- {% capture content %} -->
{% include section.html %}

{% include list.html data="alumni" component="portrait" filter="role != 'pi'" %}

{% include section.html %}
<!-- {% endcapture %} -->

<!-- {% include grid.html style="square" content=content %} -->




