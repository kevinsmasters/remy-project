---
layout: default
title: Remington Scott Masters Upsate NY Photography | Portfolio
body_class: sub_page
---
{% include hero-area.html %}
<section class="portfolio_section" id="portfolio">
  <div class="jumbotron about_me">
    <div class="container text-center">
      <div class="row">
        <div class="col-8 offset-2">
          <h1 class="display-3">Portfolio</h1>
          <p class="lead" title="put a summary of your photography services">This is a template for a simple marketing or informational website. It includes a large callout called a jumbotron and three supporting pieces of content. Use it as a starting point to create something more unique.</p>
        </div>
      </div>
    </div>
  </div>
  <div class="container">
    <div class="portfolio_new grid">
      {% for photo in site.photos %}
        <div class="grid-item">
          <img src="{{ site.baseurl }}{{ photo.img }}" alt="{{ photo.alt }}" />
          <div class="btn-box">
            <a href="" class="btn-1">
              <i class="fa fa-share-alt" aria-hidden="true"></i>
            </a>
          </div>
        </div>
      {% endfor %}
    </div>
    <div>
      <a href="{{ site.baseurl }}/portfolio.html" class="read_btn">
        See More
      </a>
    </div>
  </div>
</section>
{% include contact-section.html %}
{% include footer-section.html %}