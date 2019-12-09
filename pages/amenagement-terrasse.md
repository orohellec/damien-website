---
layout: default
title: amenagement-terrasse
---


<h1 class="text-center my-5">amenagement terrasse</h1>

<div class="text-center mb-5 mx-5">
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Ut consectetur dolor at efficitur vulputate. Quisque ac enim malesuada, sollicitudin eros at, imperdiet ipsum. Suspendisse convallis placerat velit, et dictum est fermentum et. Donec ullamcorper condimentum vehicula. Nunc porta velit id interdum pulvinar. In dapibus dictum efficitur. Integer nibh quam, congue vitae odio in, interdum vestibulum velit. Cras consequat luctus turpis, ut mollis eros consectetur sit amet. Integer ut ultrices orci, at sollicitudin nibh.</p>
</div>

<div class="row mx-5 mb-5">
  {% assign image_files = site.static_files | where: "patio", true %}
  {% for myimage in image_files %}
    {% for i in (1..6) %}
      <div class="col-12 col-md-6 col-lg-4 mb-3">
        <img src="{{ site.url }}/{{ myimage.path }}" class="img-fluid" alt="terrasse"/>
      </div>
    {% endfor %}
  {% endfor %}
</div>

