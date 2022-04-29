---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: DeiProfundis
subtitle: Theology | Ethics | Liberation | Jesus
hero_height: is-fullwidth
post-listlong: true
image: chi.jpg
hero_color: is-white
---
{% for post in site.posts limit: 8 %}
{% include post-list.html %}
{% endfor %}
