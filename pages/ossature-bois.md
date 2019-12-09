---
layout: default
title: ossature-bois
---

<h1 class="text-center my-5 font-weight-bold rounded categorie">Ossature Bois</h1>
<div class="container-fluid">
  <div class="row justify-content-center">
    <div class="col-12 col-md-11 col-xl-11">
      <div class="text-justify mb-5">
        <p>{{ site.data.wood.description }}</p>
      </div>
      <div class="row mb-5">
        {% assign image_files = site.static_files | where: "wood", true %}
        {% for myimage in image_files %}
          {% for i in (1..6) %}
            <div class="col-12 col-md-6 col-lg-4 mb-3">
              <img src="{{ site.url }}/{{ myimage.path }}" class="img-fluid" alt="cuisine"/>
            </div>
          {% endfor %}
        {% endfor %}
      </div>
    </div>
  </div>
</div>