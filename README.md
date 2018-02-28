<!DOCTYPE html>
<html>
<title>BLOG DE BUSINESS VILLAGE</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://fonts.googleapis.com/css?family=Montserrat">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
<style>
body,h1 {font-family: "Montserrat", sans-serif}
img {margin-bottom: -7px}
.w3-row-padding img {margin-bottom: 12px}
</style>
<body>
<div id="bloc_page">
        <header>
            <img src="small_logo.jpg" alt="Logo_page" title="Accueil" id="logo"/>
<nav class="w3-sidebar w3-black w3-animate-top w3-xxlarge" style="display:none;padding-top:150px" id="mySidebar">
  <a href="javascript:void(0)" onclick="w3_close()" class="w3-button w3-black w3-xxlarge w3-padding w3-display-topright" style="padding:6px 24px">
    <i class="fa fa-remove"></i>
  </a>
  <div class="w3-bar-block w3-center">
    <a href="http://www.business-village.biz" class="w3-bar-item w3-button w3-text-grey w3-hover-black">A propos</a>
    <a href="http://www.business-village.biz/index.php/espaces-new-tech" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Du côté de nos séminaires</a>
    <a href="https://www.facebook.com/pg/businessvillage.biz/reviews/?ref=page_internal" class="w3-bar-item w3-button w3-text-grey w3-hover-black">L'avis de nos internautes</a>
    <a href="http://www.business-village.biz/index.php/sophie-et-philippe-nos-valeurs" class="w3-bar-item w3-button w3-text-grey w3-hover-black">Contactez-nous!</a>
  </div>
</nav>

<div class="w3-content" style="max-width:1500px">

<div class="w3-opacity">
<span class="w3-button w3-xxlarge w3-white w3-right" onclick="w3_open()"><i class="fa fa-bars"></i></span> 
<div class="w3-clear"></div>
<header class="w3-center w3-margin-bottom">
  <h1><b>BLOG DE BUSINESS VILLAGE</b></h1>
  <p><b>Du coeur dans le Business !</b></p>
  <p class="w3-padding-16"><button class="w3-button w3-black" onclick="myFunction()">+/-</button></p>
</header>
</div>

<div class="w3-row" id="myGrid" style="margin-bottom:128px">
  <div class="w3-third">
    <img src="20180116_075713.jpg" style="width:100%">
    <img src="20180116_224617.jpg" style="width:100%">
    <img src="20180118_091431.jpg" style="width:100%">
    <img src="aifel.jpg" style="width:100%">
    <img src="20180116_222359.jpg" style="width:100%">
    <img src="20180116_100706.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="Business Village.JPG" style="width:100%">
    <img src="boules lumineuses sur la piscine.jpg" style="width:100%">
    <img src="Central.png" style="width:100%">
    <img src="Cottage.jpg" style="width:100%">
    <img src="meetingsuite1.jpg" style="width:100%">
    <img src="meat_1.jpg" style="width:100%">
	<img src="../BUSINESS VILLAGE/Photos BUSINESS VILLAGE/PICARD.jpg" style="width:100%">
  </div>

  <div class="w3-third">
    <img src="Cottage chambre royale.jpg" style="width:100%">
    <img src="cabane-2personnes2.jpg" style="width:100%">
    <img src="Meeting Suite.jpg" style="width:100%">
    <img src="38c.jpg" style="width:100%">
    <img src="../BUSINESS VILLAGE/Photos BUSINESS VILLAGE/Pavillon Blanc.jpg" style="width:100%">
    <img src="../BUSINESS VILLAGE/Photos BUSINESS VILLAGE/petitdejeuner-terasse2.jpg" style="width:100%">
  </div>
</div>

</div>

<footer class="w3-container w3-padding-64 w3-light-grey w3-center w3-opacity w3-xlarge" style="margin-top:128px"> 
  <i class="fa fa-facebook-official w3-hover-opacity"></i>
  <i class="fa fa-instagram w3-hover-opacity"></i>
  <i class="fa fa-snapchat w3-hover-opacity"></i>
  <i class="fa fa-linkedin w3-hover-opacity"></i>
  <p class="w3-medium">Visitez notre site internet : <a href="http://www.business-village.biz" target="_blank" class="w3-hover-text-green">Business Village</a>
	</p>
</footer>
 
<script>

	function myFunction() {
    var x = document.getElementById("myGrid");
    if (x.className === "w3-row") {
        x.className = "w3-row-padding";
    } else { 
        x.className = x.className.replace("w3-row-padding", "w3-row");
    }
}

function w3_open() {
    document.getElementById("mySidebar").style.width = "100%";
    document.getElementById("mySidebar").style.display = "block";
}

function w3_close() {
    document.getElementById("mySidebar").style.display = "none";
}
</script>

</body>
</html>

