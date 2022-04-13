---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: page
title: DeiProfundis
subtitle: Theology | Ethics | Liberation
hero_image: /assets/images/chi.jpg
hero_height: is-fullwidth

---

Dei Profundis was for many years the primary blog of <a href="http://mariagwyn.com/">Maria Gwyn McDowell</a>. For the last few years, she has focused on blogging at <a href="https://womenintheology.org/">Women in Theology</a> where you can read <a href="https://womenintheology.org/author/mariagwyn/">her most current contributions</a> to the theological blogosphere. She is planning to come back to Dei Profundis. But for the moment, it remains available as an archive of interesting conversation.

{% for post in site.posts limit: 8 %}
{% include post-list.html %}
{% endfor %}
