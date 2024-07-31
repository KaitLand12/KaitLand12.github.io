---
layout: archive
title: "Games"
permalink: /games/
author_profile: true
---

{% include base_path %}
## Penguin Run

<img src='https://github.com/KaitLand12/Portfolio/assets/81109745/45de08cd-9b75-4e6d-9044-d71f216fb988'>
* 2D Platformer made on Unity

* Sprites, props, and backgrounds drawn through Adobe Illustrator
* Animations made on Adobe Animate and Unity
* Music from Pixabay


{% for post in site.games %}
  {% include archive-single.html %}
{% endfor %}

