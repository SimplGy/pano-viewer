---
layout: base
---

# Pano Viewer
### A beautiful, high-res way to explore and share your panorma photos.

<ul class="panos">
  {% for file in site.static_files %}
    {% if file.path contains 'panos/full-size' %}
      <li>
        <a href="{{ site.baseurl }}{{ file.path }}" title="panoramic image">
          <img src="{{ site.baseurl }}/panos/thumbs/{{ file.name }}" />
        </a>
      </li>
    {% endif %}
  {% endfor %}
</ul>








