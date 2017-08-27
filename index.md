---
title: Home
layout: page
group: "navigation"
---


<!-- Features -->

<div class="feature-items">

  <div class="feature-item">
    <span class="feature-item__icon fa fa-gears"></span>
    <div class="feature-item__body">
      <span class="feature-item__title">Custom</span>
      <span class="feature-item__description">
        Completely customisable and deployable with a Dockerfile and Heroku
      </span>
    </div>
  </div>

  <div class="feature-item">
    <span class="feature-item__icon fa fa-lock"></span>
    <div class="feature-item__body">
      <span class="feature-item__title">Secure</span>
      <span class="feature-item__description">
        Self-hosted solution for data transmission and storage
      </span>
    </div>
  </div>

  <div class="feature-item">
    <span class="feature-item__icon fa fa-heart"></span>
    <div class="feature-item__body">
      <span class="feature-item__title">Free</span>
      <span class="feature-item__description">
        Open Source. Powered by community contributions
      </span>
    </div>
  </div>

</div>


[Learn More](#learn-more){:.link-main}

<span id="learn-more"></span>

This repository represents a listing of Open Source Bots that have been contributed by the [Cisco Spark for Developers](https://developer.ciscospark.com) community.

We understand that there is no one size fits all solution when it comes to Bots and Integrations. Some customers will choose extend the functionality of Spark using the [Spark Depot](https://depot.ciscospark.com) directly, while others will use an Application Integration service such as Built.io or Kore.ai. While others will opt to build and host their own Bots.

This project is designed to address that need, this repository contains free and open source Bot projects for various enterprise applications.

<br>

## Available Bots by Application <a class="btn-github" href="https://github.com/promptworks/ciscospark-theme" target="_blank" alt="view on github"><img class="btn-github" src="{{ site.url }}/assets/img/btn-github.png" /></a>

<br>
<div class="card-items">
  {% for bot in site.bots %}
  {% include bot-item.html %}
  {% endfor %}
</div>


## [Best practices and How to contribute ►]({{site.url}}/info){:.center}

