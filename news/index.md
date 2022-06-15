---
title: News
nav:
  order: 6
  tooltip: Laboratory News
---

# <i class="fas fa-feather-alt"></i>News

{% include section.html %}

{% include search-info.html %}

{% capture col1content %}
{%- include figure.html image=page.image -%}
{% endcapture %}
{% capture col2content %}
{% include list.html data="posts" component="post-excerpt" filters="category: news" %}
{% endcapture %}

{% include two-col.html col1=col1content col2=col2content %}

