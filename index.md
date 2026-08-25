---
layout: home
author_profile: false
title: Home
classes: wide
---

<div class="profile-home">
  {% include profile_identity.html %}

  <main class="profile-home__content">
    <section class="home-intro" id="about">
      <h2>About me</h2>
      <p>I studied Quantitative Sciences at Emory University with a focus in biology. I’m interested in working with all kinds of data, whether it comes from biology, finance, or geospatial analysis. I currently work at Capital One as a business analyst, where I focus on credit line increase requests.</p>
      <p>This website is where I share ongoing projects, research, and photographs from the places I’ve explored.</p>
    </section>

    <section class="selected-work" aria-labelledby="selected-work-title">
      <h2 id="selected-work-title">Projects</h2>

      <a class="work-row" href="https://emory-crime-map.vercel.app/">
        <span class="work-row__mark" aria-hidden="true">⛓</span>
        <span class="work-row__body"><strong>Emory Crime</strong><small>Mapping public campus crime data.</small></span>
        <span class="work-row__arrow" aria-hidden="true">→</span>
      </a>
      <a class="work-row" href="{{ '/national-parks/' | relative_url }}">
        <span class="work-row__mark" aria-hidden="true">🌲</span>
        <span class="work-row__body"><strong>National Parks</strong><small>Photographs from the landscapes I visit.</small></span>
        <span class="work-row__arrow" aria-hidden="true">→</span>
      </a>
      <a class="work-row" href="{{ '/staph-research/' | relative_url }}">
        <span class="work-row__mark" aria-hidden="true"><i class="fas fa-dna"></i></span>
        <span class="work-row__body"><strong>Staph Genomics</strong><small>Machine learning and dimensionality reduction for bacterial genomes.</small></span>
        <span class="work-row__arrow" aria-hidden="true">→</span>
      </a>
    </section>

    {% include comments.html comments_slug="about" preview_limit=3 %}
  </main>
</div>
