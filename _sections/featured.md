--- 
title: Featured Critters
order: 2
icon: fa-image
---

<style>

* {
  box-sizing: border-box;
}

/* Position the image container (needed to position the left and right arrows) */
.containersg {
  position: relative;
  width: 100%;
  margin: auto;
  background-color: #222;
  max-width: 900px;
}

/* Hide the images by default */
.mySlides {
  display: none;
  cursor: pointer;
}

/* Add a pointer when hovering over the thumbnail images */
.cursor {
  cursor: pointer;
}

/* Next & previous buttons */
.prevsg,
.nextsg {
  cursor: pointer;
  position: absolute;
  top: 40%;
  width: auto;
  padding: 16px;
  margin-top: -50px;
  color: white;
  font-weight: bold;
  font-size: 20px;
  border-radius: 0 3px 3px 0;
  user-select: none;
  -webkit-user-select: none;
  border: 0;
}

/* Position the "next button" to the right */
.nextsg {
  right: 0;
  border-radius: 3px 0 0 3px;
}

.prevsg {
  left: 0;
  border-radius: 3px 0 0 3px;
}

/* On hover, add a black background color with a little bit see-through */
.prevsg:hover,
.nextsg:hover {
  background-color: rgba(0, 0, 0, 0.8);
}

/* Number text (1/3 etc) */
.numbertext {
  color: #f2f2f2;
  font-size: 12px;
  padding: 8px 12px;
  position: absolute;
  top: 0;
}

/* Container for image text */
.caption-container {
  text-align: center;
  background-color: #222;
  padding: 2px 16px;
  color: white;
  height: 50px;
  line-height: 35px;
  text-overflow: ellipsis;
  overflow: hidden;
  white-space: nowrap;
}

.rowsg {
  margin: auto;
  display: block;
}
.rowsg:after {
  content: "";
  display: table;
  clear: both;
}

/* Six columns side by side */
.columnsg {
  float: left;
  width: 25%;
}

/* Add a transparency effect for thumnbail images */
.demo {
  opacity: 0.6;
}

.active,
.demo:hover {
  opacity: 1;
}

</style>

<div class="containersg">

  <div class="mySlides">
    <div class="numbertext">1 / 4</div>
      <img src="/pictures/octopus_classof2018.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides">
    <div class="numbertext">2 / 4</div>
      <img src="/pictures/bunny_pink.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides">
    <div class="numbertext">3 / 4</div>
      <img src="/pictures/rat_angel.jpg" style="width:100%" onclick="url()">
  </div>
  <div class="mySlides">
    <div class="numbertext">4 / 4</div>
      <img src="/pictures/bat_blackandwhite.jpg" style="width:100%" onclick="url()">
  </div>

  <a class="prevsg" onclick="plusSlides(-1)">&#10094;</a>
  <a class="nextsg" onclick="plusSlides(1)">&#10095;</a>

  <div class="caption-container">
    <p id="caption"></p>
  </div>


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

<script>

var slideIndex = 1;
showSlides(slideIndex);

// Next/previous controls
function plusSlides(n) {
  showSlides(slideIndex += n);
}

// Thumbnail image controls
function currentSlide(n) {
  showSlides(slideIndex = n);
}

function showSlides(n) {
  var i;
  var slides = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  var captionText = document.getElementById("caption");
  if (n > slides.length) {slideIndex = 1}
  if (n < 1) {slideIndex = slides.length}
  for (i = 0; i < slides.length; i++) {
    slides[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" active", "");
  }
  slides[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " active";
  captionText.innerHTML = dots[slideIndex-1].alt;
} 

function url() {
  location.href= '/gallery';
}
</script>
