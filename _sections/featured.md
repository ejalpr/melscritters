--- 
title: Featured Critters
order: 3
icon: fa-heart
---
<link rel="stylesheet" type="text/css" href="assets/css/slideshow.css">

<div class="containersg">

<!-- MAIN PHOTO -->

  <div class="mySlides fade">
    <div class="numbertext">1 / 4</div>
      <img src="/pictures/octopus_classof2018.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides fade">
    <div class="numbertext">2 / 4</div>
      <img src="/pictures/bunny_pink.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides fade">
    <div class="numbertext">3 / 4</div>
      <img src="/pictures/rat_angel.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides fade">
    <div class="numbertext">4 / 4</div>
      <img src="/pictures/bat_blackandwhite.jpg" style="width:100%" onclick="url()">
  </div>

  <a class="prevsg" onclick="plusSlides(-1)">&#10094;</a>
  <a class="nextsg" onclick="plusSlides(1)">&#10095;</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>

<!-- THUMBNAIL -->

  <div class="rowsg">
    <div class="columnsg">
      <img class="demo cursor" src="/pictures/octopus_classof2018.jpg" style="width:100%" onclick="currentSlide(1)" alt="Octopus staring into the distance">
    </div>
    <div class="columnsg">
      <img class="demo cursor" src="/pictures/bunny_pink.jpg" style="width:100%" onclick="currentSlide(2)" alt="Gamer Bunny">
    </div>
    <div class="columnsg">
      <img class="demo cursor" src="/pictures/rat_angel.jpg" style="width:100%" onclick="currentSlide(3)" alt="R.I.P (Rat in Peace)">
    </div>
    <div class="columnsg">
      <img class="demo cursor" src="/pictures/bat_blackandwhite.jpg" style="width:100%" onclick="currentSlide(4)" alt="Black and White Bats">
    </div>
  </div>




</div>

<script type="text/javascript" src="assets/js/slideshow.js"></script>
