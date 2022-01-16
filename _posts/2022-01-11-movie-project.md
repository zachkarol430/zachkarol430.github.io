---
layout: posts
title: Movie website 
comments: true
---

Over the last few months, I have been working on a website which will serve two purposes

1. The website will allow users to get basic information about a movie quickly without having to click through a bunch of sites

2. The website would store my movies I have watched and their rating as well. This allows my friends to see what I have been watching, but also allows me to keep track of the movies I watched

### Cool things I did

I have utilized cloud computing using Heroku to scrape google for movie info. The program runs in the cloud and then gives the results back to your computer, meaning your computer is not doing any computations. 

I have also used multiprocessing, which is running multiple tasks in parallel instead of running tasks serially. Running my task in parallel took so more code to do, but ended up making it much faster. 

### Problems with the site

I am currently facing issues with movies which are in franchises and those that are animated can give incorrect responses. I am looking at ways around this and possible solutions include checking if a movie is animated or franchised first and then from there adding keyterms to get the right results.



If there are any issues or bugs please let me know in the comments

Last note: The website may take time to boot up, so be patient

[movie site](https://evening-scrubland-99469.herokuapp.com/){:target="_blank"}

{% if page.comments == true %}
  {% include comments.html %}
{% endif %}