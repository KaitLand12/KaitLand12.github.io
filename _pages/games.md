---
layout: archive
title: "Games"
permalink: /games/
author_profile: true
---

{% include base_path %}
## Penguin Run

<img src='https://github.com/KaitLand12/Portfolio/assets/81109745/45de08cd-9b75-4e6d-9044-d71f216fb988'>
2D Platformer made on Unity

Sprites, props, and backgrounds drawn through Adobe Illustrator
Animations made on Adobe Animate and Unity
Music from Pixabay

[![Youtube Video](https://img.youtube.com/vi/q8xg1pab1MY/0.jpg)](https://www.youtube.com/watch?v=q8xg1pab1MY)

<iframe width="560" height="315" src="https://www.youtube.com/embed/q8xg1pab1MY?si=mydetozfd1yKQiZK" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" referrerpolicy="strict-origin-when-cross-origin" allowfullscreen></iframe>

{% for post in site.games %}
  {% include archive-single.html %}
{% endfor %}

