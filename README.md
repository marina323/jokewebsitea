# jokewebsitea
<!DOCTYPE html>
<html>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/3/w3.css">

<body  bgcolor="#ffccff">


<!-- Navigation bar -->
<nav class="w3-bar w3-black">
  <a href="#home" class="w3-button w3-bar-item">Home</a>
  <a href="#band" class="w3-button w3-bar-item">Articles</a>
  <a href="#about us" class="w3-button w3-bar-item">About Us</a>
  <a href="#contact" class="w3-button w3-bar-item">Contact Us</a>
</nav>


<!-- Slide Show -->
<section>
  <img class="mySlides" src="image1.jpg" alt="image1" width="750" height="550">

</section>


<script>

// Automatic Slideshow - change image every 3 seconds
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
  setTimeout(carousel, 3000);
}
</script>


<!-- TEXT -->
<section class="w3-container w3-center w3-content" style="max-width:600px">
 
 <h2 class="w3-wide"><font color="white">WANT TO WIN MARINA'S HEART?</font></h2>
  
  <p class="w3-opacity"><i> <font color="white">A step by step tutorial</font> </i></p>
  
  <p class="w3-justify"> Are you a male nerd who has tried time and time again to win Marina's heart but have unfortunately failed to accomplish said task? You might not be not nerdy enough, somehow fail to provide sufficient intellectual stimulation, or are piss-poor at social engineering ("social skills" in normie-lingo) to a degree even Marina can not ignore when looking for a mate. </p>

  <p class="w3-justify">With this website, we hope to guide the interested male nerd population on how to win Marina’s heart by revealing the ways in which Marina evaluates potential mates with the help of a comprehensive list of requirements.</p>

<div class="danger">
  <p><strong>Important!</strong> If you are not a male nerd, do not waste your time -- you are automatically ruled out as a potential mate for Marina.</p>
</div>

<h2>A comprehensive list of Marina’s requirements </h2>
<ul><a href="https://www.w3schools.com/" target="_blank">Don’t be a gay faggot</a></ul>
<ul><a href="https://www.w3schools.com/" target="_blank">Stop being a vagina</a></ul>
<ul><a href="https://www.w3schools.com/" target="_blank">Grow a dick</a></ul>
</section>


</body>
</html>
