---
title: Contact
nav:
  order: 5
  tooltip: Email, address, and location
---

# {% include icon.html icon="fa-regular fa-envelope" %}Contact

We welcome motivated students, postdoctoral researchers, technicians, research scientists and undergraduate internships with backgrounds in biology, medicine, bioinformatics, computational science, engineering, or related fields. For Master or Ph.D. students, please check the official programs of [GIBH](https://gibh.cas.cn/). If you are passionate about exploring the frontiers of cellular lineage biology and regenerative medicine, we encourage you to contact us. And hope you can become a part of the PengLab family!

<div style="display: flex; justify-content: center; gap: 20px; flex-wrap: wrap;">
  <div style="width: 200px;">
    {% include figure.html image="images/pgd_QR.png" caption="Profile of Prof. Peng" %}
  </div>
  <div style="width: 200px;">
    {% include figure.html image="images/wechat.jpg" caption="WeChat accounts of PengLab" %}
  </div>
  <div style="width: 200px;">
    {% include figure.html image="images/gibh.jpg" caption="WeChat accounts of GIBH" %}
  </div>
</div>

{%
  include button.html
  type="email"
  text="peng_guangdun@gibh.ac.cn"
  link="peng_guangdun@gibh.ac.cn"
%}
{%
  include button.html
  type="phone"
  text="(+86)020-89851649"
  link="+86-020-89851649"
%}
{%
  include button.html
  type="address"
  tooltip="Our location on Google Maps for easy navigation"
  link="https://maps.app.goo.gl/1m5PjZP7bPApNJ9t8"
%}

{% include section.html %}

{% capture col1 %}

{%
  include figure.html
  image="images/gibh1.jpg"
  caption="Guangzhou Institutes of Biomedicine and Health, Chinese Academy of Sciences"
%}

{% endcapture %}

{% capture col2 %}

{%
  include figure.html
  image="images/gibh2.jpg"
  caption="Human Cell Lineage Atlas Facility"
%}

{% endcapture %}

{% include cols.html col1=col1 col2=col2 %}

{% include section.html dark=true %}
<!-- 
{% capture col1 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col2 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %}

{% capture col3 %}
Lorem ipsum dolor sit amet  
consectetur adipiscing elit  
sed do eiusmod tempor
{% endcapture %} -->

{% include cols.html col1=col1 col2=col2 col3=col3 %}
