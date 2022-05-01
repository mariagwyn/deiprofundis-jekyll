---
layout: page
title: Tests
permalink: /test/
image: chi.jpg
support: [gallery, jquery]
---
<!-- PhotoSwipe -->
<div class="photoswipe-gallery">
  {% include photo.html
     url="/assets/images/chi.jpg"
     thumb_width="200" alt="Adorable creature"
     full_width="600" full_height="380"
  %}
</div>

another
<div class="photoswipe-gallery">
  {% include photo.html
      url="/assets/images/myrrh-bearing1.jpg"
      thumb_width="200" thumb_height="230"
      full_width="400" full_height="200"
      caption="Caption will show when the photo is enlarged" alt="Alt shows if the photo cannot be shown"
  %}
</div>

{% include photo.html gallery="gallery-pascha2022" %}
