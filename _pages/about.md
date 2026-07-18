---
permalink: /
title: ""
layout: home
author_profile: false
redirect_from:
  - /about/
  - /about.html
---

<main class="home-page">
  <section class="hero" aria-labelledby="intro-title">
    <div class="hero__copy">
      <h1 id="intro-title">Adamson Bryant</h1>
      <div id="about" class="hero__about">
        <p> I am a PhD candidate in Economics at Brown University studying urban inequality, with additional interests in methods and labor market inequality. </p>
        <p>I'm an avid runner who revels in time spent in the mountains. When I'm not outdoors, you can find me tearing out my hair watching Manchester United or consuming history books from any era or region.</p>
      </div>
      <div class="hero__actions" aria-label="Quick links">
        <a class="text-link text-link--strong" href="#research">Research <span aria-hidden="true">↘</span></a>
        <a class="text-link text-link--strong" href="{{ site.baseurl }}/files/Adamson_Bryant_CV_September2025.pdf" target="_blank" rel="noopener">CV <span aria-hidden="true">↗</span></a>
        <a class="text-link text-link--strong" href="mailto:adamson_bryant@brown.edu">Email <span aria-hidden="true">↗</span></a>
      </div>
    </div>
    <figure class="hero__image">
      <img src="{{ '/images/me_tetons.JPG' | relative_url }}" alt="Adamson Bryant in the Grand Tetons" width="2049" height="1536" loading="eager" fetchpriority="high" decoding="async">
      <figcaption>Grand Teton National Park · 2022</figcaption>
    </figure>
  </section>

  <section id="research" class="home-section" aria-labelledby="research-title">
    <div class="section-heading"><h2 id="research-title">Research</h2></div>
    <div class="research-list">
      <article class="research-item">
        <div class="research-item__number">01</div>
        <div class="research-item__body">
          <div class="research-item__meta">Working paper</div>
          <h3>Place-Based Policies for Neighborhood Improvement: Evidence from Promise Zones</h3>
          <details class="research-abstract">
            <summary>Abstract <span aria-hidden="true">+</span></summary>
            <p>Despite growing evidence that neighborhoods play a critical role in shaping economic mobility and well-being, effective policies to address neighborhood disadvantage remain elusive. This study evaluates the impact of the Promise Zone program, which aims to revitalize disadvantaged neighborhoods through streamlined federal support and grant incentives. I use an event study framework with newly obtained data on the location of failed finalist applications as a comparison group to estimate the program’s effects. The results reveal significant improvements in poverty, household incomes, and employment in Promise Zone neighborhoods, particularly in later-designated zones and initially low-status neighborhoods. I also find that effects are driven partly by changes in residential composition, and that Promise Zones appear to induce positive spillovers in adjacent areas.</p>
          </details>
          <div class="research-links"><a href="https://arxiv.org/abs/2503.05946" target="_blank" rel="noopener">arXiv <span aria-hidden="true">↗</span></a></div>
        </div>
      </article>
      <article class="research-item"><div class="research-item__number">02</div><div class="research-item__body"><div class="research-item__meta">Work in progress</div><h3>Gun Violence and Business Activity</h3><p>With <a href="https://www.pankabencsik.com">Panka Bencsik</a> and <a href="https://www.jessebruhn.com">Jesse Bruhn</a>.</p></div></article>
      <article class="research-item"><div class="research-item__number">03</div><div class="research-item__body"><div class="research-item__meta">Work in progress</div><h3>Shift-Share Designs with High-Dimensional Confounders</h3></div></article>
      <article class="research-item"><div class="research-item__number">04</div><div class="research-item__body"><div class="research-item__meta">Work in progress</div><h3>Homelessness and the Housing Market</h3></div></article>
    </div>
  </section>

  <section id="outdoors-preview" class="home-section outdoors-preview" aria-labelledby="outdoors-title">
    <div class="section-heading section-heading--wide"><div><h2 id="outdoors-title">Outdoors</h2></div><a class="text-link" href="{{ site.baseurl }}/outdoors/">View all <span aria-hidden="true">↗</span></a></div>
    <div class="preview-grid">
      <figure><img src="{{ site.baseurl | default: '.' }}/images/outdoors/optimized/huayhuash6.jpeg" alt="Mountain landscape in the Cordillera Huayhuash" loading="lazy" width="1800" height="1350"><figcaption>Huayhuash · May 2026</figcaption></figure>
      <figure><img src="{{ site.baseurl | default: '.' }}/images/outdoors/optimized/sedona.jpeg" alt="Red rock landscape near Sedona" loading="lazy" width="1800" height="1350"><figcaption>Sedona · March 2026</figcaption></figure>
      <figure><img src="{{ site.baseurl | default: '.' }}/images/outdoors/optimized/dibona.jpeg" alt="Mountain landscape in the Dolomites" loading="lazy" width="1800" height="1350"><figcaption>Dolomites · July 2025</figcaption></figure>
    </div>
  </section>
</main>
