---
layout: default
title: "Damien Website"
---

<div id="carouselExampleIndicators" class="carousel slide d-none d-lg-block" data-ride="carousel">
  <ol class="carousel-indicators">
    <li data-target="#carouselExampleIndicators" data-slide-to="0" class="active"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="1"></li>
    <li data-target="#carouselExampleIndicators" data-slide-to="2"></li>
  </ol>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img class="d-block w-100" src="{{site.url}}/assets/img/carrousel/panoramic.jpg" alt="First slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>TITRE</h5>
        <p>text</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="{{site.url}}/assets/img/carrousel/panoramic.jpg" alt="Second slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>TITRE</h5>
        <p>text</p>
      </div>
    </div>
    <div class="carousel-item">
      <img class="d-block w-100" src="{{site.url}}/assets/img/carrousel/panoramic.jpg" alt="Third slide">
      <div class="carousel-caption d-none d-md-block">
        <h5>TITRE</h5>
        <p>text</p>
      </div>
    </div>
  </div>
  <a class="carousel-control-prev" href="#carouselExampleIndicators" role="button" data-slide="prev">
    <span class="carousel-control-prev-icon" aria-hidden="true"></span>
    <span class="sr-only">Previous</span>
  </a>
  <a class="carousel-control-next" href="#carouselExampleIndicators" role="button" data-slide="next">
    <span class="carousel-control-next-icon" aria-hidden="true"></span>
    <span class="sr-only">Next</span>
  </a>
</div>

<div class="container-fluid">
  <div class="row justify-content-center my-5">
    <div class="col-12 col-md-11">
      <div class="row mb-5">
        <div class="col-12 col-md-6 mb-5 text-center">
          <img src="{{ site.url }}/assets/img/profil/damien.jpg" alt="Damien Benard" class="img-fluid rounded" />
        </div>
        <div class="col-12 col-md-6 text-center my-auto ">
          <h1>Damien Benard</h1>
          <h2>Artisan Menuisier</h2>
          <h3>Se déplace sur Auray, Vannes...</h3>
          <h4>Tel: 06 58 78 96 58</h4>
          <h4>email: example@gmail.com</h4>
        </div>
      </div>
      <div class="row mb-5">
        <div class="col-12 text-justify">
          <p>{{ site.data.home.description }}</p>
        </div>
      </div>
    </div>
  </div>
</div>



