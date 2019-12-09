---
layout: default
title: amenagement-cuisine
---

<h1 class="text-center my-5">amenagement cuisine</h1>

<div class="text-justify mb-5 mx-5">
  {% for kitchen_hash in site.data.pages %}
  {% assign kitchen = kitchen_hash[1] %}
  <p>{{ kitchen.description }}</p>
  <p>{{ site.baseurl }}</p>
  {% endfor %}
</div>

<div class="row mx-5 mb-5">
  {% assign image_files = site.static_files | where: "kitchen", true %}
  {% for myimage in image_files %}
    {% for i in (1..6) %}
      <div class="col-12 col-md-6 col-lg-4 mb-3">
        <img src="{{ site.url }}/{{ myimage.path }}" class="img-fluid" alt="cuisine"/>
      </div>
    {% endfor %}
  {% endfor %}
</div>
