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
        Totally customisable to suit your requirements
      </span>
    </div>
  </div>

  <div class="feature-item">
    <span class="feature-item__icon fa fa-lock"></span>
    <div class="feature-item__body">
      <span class="feature-item__title">Secure</span>
      <span class="feature-item__description">
        Deploy to your preferred Cloud for data transmission and storage
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

Cisco Spark Ambassador PowerUps are a collection of community created Open Source Bots and Integrations. Designed to be a kickstarter to meet the requirements of complex enterprise software configurations and satisfy data storage and transmission considerations.

Contributions to this collection are provided as a reference implementation which will provide a solid set of functionality that works with most  default configurations of the respective application.

Each PowerUp has been made available under an Open Source license (typically MIT License) allowing you to take the reference implementation of the Bot/Integration and customise freely to your needs.

Many enterprises have strict InfoSec requirements around where their Bots/Integrations/Applications can be hosted along with restrictions around data storage and transmission. To address this, all PowerUps in this collection can be deployed in your preferred Cloud and every repository contains a precomposed Dockerfile, along with a Deploy to Heroku button allowing you to spin up PowerUps on Heroku in just a few clicks.

<br>

## Available Bots by Application <a class="btn-github" href="https://github.com/promptworks/ciscospark-theme" target="_blank" alt="view on github"><img class="btn-github" src="{{ site.url }}/assets/img/btn-github.png" /></a>

<br>
<div class="card-items">
  {% for bot in site.bots %}
  {% include bot-item.html %}
  {% endfor %}
</div>


## [Best practices and How to contribute ►]({{site.url}}/info){:.center}

