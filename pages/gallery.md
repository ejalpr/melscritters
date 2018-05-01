---
layout: page
title: Gallery
order: 2
cover-photo: /pictures/banner.jpg
cover-photo-alt: banner
permalink: /gallery
icon: fa-image
---
<link rel="stylesheet" type="text/css" href="assets/css/collage.css">
<link rel="stylesheet" type="text/css" href="assets/css/modal.css">
<script type="text/javascript" src="assets/js/modal.js"></script>

<div class="row">
  <div class="column">
    <img src="/pictures/rat_couple.jpg" style="width:100%" onclick="openModal();currentSlide(9)" 
class="hover-shadow">
    <img src="/pictures/rat_candycorn.jpg" style="width:100%" onclick="openModal();currentSlide(8)" 
class="hover-shadow">
  </div>
  <div class="column">
    <img src="/pictures/bunny_spotted.jpg" style="width:100%" onclick="openModal();currentSlide(4)" 
class="hover-shadow">
    <img src="/pictures/octopus_classof2018.jpg" style="width:100%" onclick="openModal();currentSlide(5)" 
class="hover-shadow">
    <img src="/pictures/bunny_pink.jpg" style="width:100%" onclick="openModal();currentSlide(3)" 
class="hover-shadow">
  </div>
  <div class="column">
    <img src="/pictures/rat_assorted.jpg" style="width:100%" onclick="openModal();currentSlide(7)" 
class="hover-shadow">
    <img src="/pictures/rat_angel.jpg" style="width:100%" onclick="openModal();currentSlide(6)" 
class="hover-shadow">
  </div>
  <div class="column">
    <img src="/pictures/bat_blackandwhite.jpg" style="width:100%" onclick="openModal();currentSlide(1)" 
class="hover-shadow">
    <img src="/pictures/bunny_jackalope.jpg" style="width:100%" onclick="openModal();currentSlide(2)" 
class="hover-shadow">
  </div>
</div>


<div id="myModal" class="modal">
  <span class="close cursor" onclick="closeModal()">&times;</span>
  <div class="modal-content">
    <div class="mySlides">
      <div class="numbertext">1 / 9</div>
      <img src="/pictures/bat_blackandwhite.jpg" style="width:100%">
    </div>
    <div class="mySlides">
      <div class="numbertext">2 / 9</div>
      <img src="/pictures/bunny_jackalope.jpg" style="width:100%">
    </div>
    <div class="mySlides">
      <div class="numbertext">3 / 9</div>
      <img src="/pictures/bunny_pink.jpg" style="width:100%">
    </div>
    <div class="mySlides">
      <div class="numbertext">4 / 9</div>
      <img src="/pictures/bunny_spotted.jpg" style="width:100%">
    </div>
    
    <div class="mySlides">
      <div class="numbertext">5 / 9</div>
      <img src="/pictures/octopus_classof2018.jpg" style="width:100%">
    </div>
    
    <div class="mySlides">
      <div class="numbertext">6 / 9</div>
      <img src="/pictures/rat_angel.jpg" style="width:100%">
    </div>
    
    <div class="mySlides">
      <div class="numbertext">7 / 9</div>
      <img src="/pictures/rat_assorted.jpg" style="width:100%">
    </div>
    
    <div class="mySlides">
      <div class="numbertext">8 / 9</div>
      <img src="/pictures/rat_candycorn.jpg" style="width:100%">
    </div>
    
    <div class="mySlides">
      <div class="numbertext">9 / 9</div>
      <img src="/pictures/rat_couple.jpg" style="width:100%">
    </div>
    
    <!-- Next/previous controls -->
    <a class="prev" onclick="plusSlides(-1)">&#10094;</a>
    <a class="next" onclick="plusSlides(1)">&#10095;</a>
    <!-- Caption text -->
    <div class="caption-container">
      <p id="caption"></p>
    </div>
    <!-- Thumbnail image controls -->
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(1)" alt="Black and 
White Bats">
    </div>
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(2)" alt="Jackalope">
    </div>
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(3)" alt="Pink 
Bunny">
    </div>
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(4)" alt="Spotted 
Bunny">
    </div>
    
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(5)" alt="Graduation 
Day">
    </div>
    
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(6)" alt="Angel 
Rats">
    </div>
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(7)" alt="Assorted 
Rats">
    </div>
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(8)" alt="Candy Corn 
Rats">
    </div>
    
    <div class="column">
      <img class="demo" src="/pictures/black.jpg" style="width:0%" onclick="currentSlide(9)" alt="Rat 
Couple">
    </div>
    
  </div> </div>
