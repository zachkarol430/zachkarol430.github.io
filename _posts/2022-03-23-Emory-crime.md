---
layout: posts
title: Emory Crime
tags:
  - Projects 
comments: true
---

## Crime project

I have used selenium to get all of Emory's crime data. This crime data is stored in a csv on my computer but I plan on storing this with AWS and constantly update the data. I am still working on this project but here is a map I have made of Emory's crime. This is still a work in progress but leave any comments or ideas below! If you press on the button below it will bring you to a shiny app, which is a good way to look at Emory's crime data.

<iframe seamless
src="/assets/leaflet.html" width="100%" height="500"></iframe>
<br>


<!-- mess around with iframe to get ideal shape -->
{% include buttons/shiny_button.html %}


{% if page.comments == true %}
  {% include comments.html %}
{% endif %}