---
title: Contact
nav:
  order: 7
  tooltip: Email, address, and location
---

# <i class="fas fa-envelope"></i>Contact

{%
  include link.html
  type="email"
  icon=""
  text="hevuong@umn.edu"
  tooltip=""
  link="hevuong@umn.edu"
  style="button"
%}
{%
  include link.html
  type="phone"
  icon=""
  text="(612) 626-5719" 
  tooltip=""
  link="+1-612-626-5719"
  style="button"
%}
{%
  include link.html
  type="address"
  icon=""
  text="Google Maps"
  tooltip="Lab location on Google Maps for easy navigation"
  link="https://goo.gl/maps/LbPae5VfSGAkane56"
  style="button"
%}
{:.center}

{% include section.html %}

# <i class="fas fa-mail-bulk"></i>Mailing Address

Phillips-Wangensteen Building, Rm 13-121  
516 Delaware St SE  
Minneapolis, MN 55455
{:.center}

{% capture col1 %}
{%
  include figure.html
  image="images/east.jpg"
  caption="U of MN East Bank"
%}
{% endcapture %}
{% capture col2 %}
{%
  include figure.html
  image="images/west.jpg"
  caption="U of MN West Bank"
%}
{% endcapture %}
{% include two-col.html col1=col1 col2=col2 %}
