---
title: "Bad Lauchstädt"
classes: wide
---

**These are a test images!**

<h1>Latest Images</h1>

<div class="gallery">
  {% assign image_urls = site.data.platform2_Plot1_cam1 | newline_to_br | split: '<br />' %}
  {% for url in image_urls %}
    <img src="{{ url }}" alt="Image">
  {% endfor %}
</div>

<div class="image-container"> 
  <img src="http://85.214.136.59/camhi_data/platform2/Plot1/cam1/NRT/P24031308595910.jpg" alt="test image">
</div>

## Past Month

{% include fetch_images_from_server.html folder="platform2/Plot1/cam1/archive/" %}
