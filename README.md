<!DOCTYPE html>
<html lang="en">
<head>
  <title>Plastic Pollution</title>
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/css/bootstrap.min.css">
  <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.4.1/jquery.min.js"></script>
  <script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.4.0/js/bootstrap.min.js"></script>
</head>
<style>
body {background-color:#ccccccff;}
.navbar {
  min-height: 60px; 
}
.navbar-brand {
  padding: 0 15px;
  height: 70px;
  line-height: 80px;
   margin-right: 210px;
 
 }
.navbar-toggle {
  /* (80px - button height 34px) / 2 = 23px */
  margin-top: 23px;
  padding: 9px 10px !important;
}
@media (min-width: 768px) {

  .navbar-nav > li > a {
    /* (80px - line-height of 27px) / 2 = 26.5px */
    padding-top: 26.5px;
    padding-bottom: 26.5px;
    line-height: 27px;
 }
 
 .nav.navbar-nav li a {
    color: #ffffff;
	hover: gray;
}

 .navbar-nav > li{
  margin-left:50px;
  margin-right:10px;
  font-size: 23px;
  font-family: Candara;
}

.navbar.navbar-inverse {
     margin-bottom: -20px;
    }
	
.navbar-inverse {
     background-color: #5b6e88ff;
	 border: 0;
}

img {
margin-top: -140px;
margin-left: 20px;
}

.dropdown-menu {
background-color: #8197b5ff;
}

</style>
<body>

<nav class="navbar navbar-inverse">
  <div class="container-fluid">
    <!-- Brand/logo -->
  <a class="navbar-brand" href="#">
    <img src="logo.png" alt="logo" style="width:350px;">
  </a>
  
    <ul class="nav navbar-nav">
        <li><a href="newbobo.html">Home</a></li>
      <li class="dropdown"><a class="dropdown-toggle" data-toggle="dropdown" href="#">Menu<span class="caret"></span></a>
        <ul class="dropdown-menu">
          <li><a href="newbruh.html">Cause And Effect</a></li>
          <li><a href="newbrysenhaha.html">Solution</a></li>
        </ul>
      </li>
      <li><a href="newbimby.html">About</a></li>
      <li><a href="newbimbo.html">Facts</a></li>
    </ul>
  </div>
</nav>
</body>
</body>
<body>
<div class="container-fluid">
</div>
</body>
<body>
  <meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<style>
.mySlides {display:none}
.w3-left, .w3-right, .w3-badge {cursor:pointer}
.w3-badge {height:13px;width:13px;padding:0}
</Style>
<body>

<div class="w3-container">
</div>

<div class="w3-content w3-display-container" style="max-width:1300px">
  <img class="mySlides w3-animate-fading" src="img_mountains_wide.jpg" style="width:1300px">
  <img class="mySlides w3-animate-fading" src="img_snow_wide.jpg" style="width:1300px">
  <img class="mySlides w3-animate-fading" src="sea1.png" style="width:1300px">
  <div class="w3-center w3-container w3-section w3-large w3-text-white w3-display-bottommiddle" style="width:100%">
    <div class="w3-left w3-hover-text-khaki" onclick="plusDivs(-1)">&#10094;</div>
    <div class="w3-right w3-hover-text-khaki" onclick="plusDivs(1)">&#10095;</div>
    <span class="w3-badge demo w3-border w3-transparent w3-hover-white" onclick="currentDiv(1)"></span>
    <span class="w3-badge demo w3-border w3-transparent w3-hover-white" onclick="currentDiv(2)"></span>
    <span class="w3-badge demo w3-border w3-transparent w3-hover-white" onclick="currentDiv(3)"></span>
  </div>
</div>

<script>
var slideIndex = 1;
showDivs(slideIndex);

function plusDivs(n) {
  showDivs(slideIndex += n);
}

function currentDiv(n) {
  showDivs(slideIndex = n);
}

function showDivs(n) {
  var i;
  var x = document.getElementsByClassName("mySlides");
  var dots = document.getElementsByClassName("demo");
  if (n > x.length) {slideIndex = 1}
  if (n < 1) {slideIndex = x.length}
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";
  }
  for (i = 0; i < dots.length; i++) {
    dots[i].className = dots[i].className.replace(" w3-white", "");
  }
  x[slideIndex-1].style.display = "block";
  dots[slideIndex-1].className += " w3-white";
}
var myIndex = 0;
carousel();

function carousel() {
  var i;
  var x = document.getElementsByClassName("mySlides");
  for (i = 0; i < x.length; i++) {
    x[i].style.display = "none";  
  }
  myIndex++;
  if (myIndex > x.length) {myIndex = 1}    
  x[myIndex-1].style.display = "block";  
  setTimeout(carousel, 9000);    
}
</script>
</body>
<body>
<head>
<meta name="viewport" content="width=device-width, initial-scale=1">
<style>
* {
  box-sizing: border-box;
}

body {
  margin: 0;
  font-family: Arial, Helvetica, sans-serif;
}

/* The grid: Three equal columns that floats next to each other */
.column {
  float: left;
  width: 33.33%;
  padding: 50px;
  text-align: left;
  font-size: 20px;
  cursor: pointer;
  color: #595757ff;
  margin-bottom: 35px;
}

.containerTab {
  padding: 20px;
  color: white;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Closable button inside the container tab */
.closebtn {
  float: right;
  color: white;
  font-size: 21px;
  cursor: pointer;
}
</style>
</head>
<body>
<!-- Three columns -->
<div class="row">
  <div class="column" style="background:#ccccccff">
   Plastic pollution has become one of the most pressing environmental issues<br><br>
  </div>
  <div class="column"  style="background:#ccccccff">
    Every day approximately 8 million pieces of plastic pollution find their way into our oceans.<br><br>
  </div>
  <div class="column"  style="background:#ccccccff:">
    As plastic is composed of major toxic pollutants, it has the potential to cause significant harm to the environment.
  </div>
</div>
