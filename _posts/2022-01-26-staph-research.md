---
layout: posts
title: Staph Research
comments: true
tags:
  - Research 
---

For the past couple of months I have been research the staph genome. I am using [Staphopia](https://github.com/staphopia/staphopia-r) as a tool which has thousands of public staph genomes. 

Currently looking at how staph genes accessory(not all staph have these genes) staph genes can relate to core genome(genes all staph samples have)

I will be uploading a new github repository with my machine learning model for sequence type, if I can make sure it makes sense.

## New plot 

This is a graph showing a bunch of sequence types of staph. Sequence type, is a way which bacteria are typed into groups. Here I show how all the sequence types are related in 2D space, even though each point has over 260 variables. I reduced a 260 variable plot to a dimension plot using t-SNE. Pretty cool right!

![TSNE Graph](/assets/images/TSNE.png)

{% if page.comments == true %}
  {% include comments.html %}
{% endif %}