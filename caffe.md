<!DOCTYPE html>
<html>
<title>Caffe Kita</title>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1">
<link rel="stylesheet" href="https://www.w3schools.com/w3css/4/w3.css">
<link rel="stylesheet" href="https://badoystudio.com/cloudme.fonts.googleapis.com/css?family=Inconsolata">
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.1.3/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-1BmE4kWBq78iYhFldvKuhfTAU6auU8tT94WrHftjDbrCEXSU1oBoqyl2QvZ6jIW3" crossorigin="anonymous">

<style>
body, html {
height: 100%;
font-family: "Inconsolata", sans-serif;
}

.bgimg {
background-position: center;
background-size: cover;
background-image: url("bg--caffe-kita.jpg");
min-height: 75%;
}

.menu {
display: none;
}
</style>
<body>

<!-- Links (sit on top) -->
<div class="w3-top">
<div class="w3-row w3-padding w3-black">
<div class="w3-col s3">
<a href="#" class="w3-button w3-block w3-black">HOME</a>
</div>
<div class="w3-col s3">
<a href="#about" class="w3-button w3-block w3-black">ABOUT</a>
</div>
<div class="w3-col s3">
<a href="#menu" class="w3-button w3-block w3-black">MENU</a>
</div>
<div class="w3-col s3">
<a href="#where" class="w3-button w3-block w3-black">WHERE</a>
</div>
</div>
</div>

<!-- Header with image -->
<header class="bgimg w3-display-container w3-grayscale-min" id="home">
<div class="w3-display-bottomleft w3-center w3-padding-large w3-hide-small">
<span class="w3-tag">Buka dari 06.00am-22.00pm</span>
</div>
<div class="w3-display-middle w3-center">
<span class="w3-text-white" style="font-size:90px">Cafe<br>Kita</span>
</div>
<div class="w3-display-bottomright w3-center w3-padding-large">
<span class="w3-text-white">Jl.Nangka Pasar Rebo,Jakarta Timur</span>
</div>
</header>

<!-- Add a background color and large text to the whole page -->
<div class="w3-sand w3-grayscale w3-large">

<!-- About Container -->
<div class="w3-container" id="about">
<div class="w3-content" style="max-width:700px">
<h5 class="w3-center w3-padding-64"><span class="w3-tag w3-wide">ABOUT CAFE KITA</span></h5>
<p>Caffe Kita Didirikan pada 9 Desember 2021, Caffe ini didirikan dengan konsep Scandinavian,serta nuansa yang tenang dan minimalis. Cafe Kita juga dilengkapi dengan berbagai fasilitas seperti Wifi, Live musik, dan ruangan yang terbagi menjadi dua bagian yaitu Outdoor dan Indoor,serta terdapat banyak spot foto yang menarik. Coffe kita juga mempunyai alat standart Coffe Shop dan menggunakan biji kopi berkualitas premium sehingga penikmat dapat merasakan kopi yang diinginkan.</p>
<p>Kami juga menyediakan berbagai macam Breakfast, Lunch, dan dessert. </p>
<div class="w3-panel w3-leftbar w3-light-grey">
<p><i>"Kurus atau Gendut adalah pilihan tapi makanan enak adalah kebutuhan"</i></p>
<p>-Unknown</p>
</div>
<img src="caffe-1.jpg" style="width:100%;max-width:1000px" class="w3-margin-top">
<p><strong>Jam Buka/Tutup:</strong> Setap Hari dari 06.00am-22.00pm</p>
<p><strong>Alamat:</strong> Jl.Nangka Pasar Rebo,Jakarta Timur.</p>
</div>
</div>

<!-- Menu Container -->
<div class="w3-container" id="menu">
<div class="w3-content" style="max-width:700px">

<h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">MENU</span></h5>

<div class="w3-row w3-center w3-card w3-padding">
<a href="javascript:void(0)" onclick="openMenu(event, 'Makanan');" id="myLink">
<div class="w3-col s6 tablink">Makanan</div>
</a>
<a href="javascript:void(0)" onclick="openMenu(event, 'Minuman');">
<div class="w3-col s6 tablink">Minuman</div>
</a>
</div>

<div id="Makanan" class="w3-container Menu w3-padding-48 w3-card">
<h5>Roti Bakar</h5>
<p class="w3-text-grey">Dengan Berbagai Macam Rasa,Coklat,Vanilla,Strawberry,Oreo</p><br>

<h5>Breakfast</h5>
<p class="w3-text-grey">Daging ayam lembut yang di balut dengan tepung yang renyah</p><br>
<p class="w3-text-grey">Egg muffin</p><br>
<p class="w3-text-grey">Saussage muffin</p><br>
<p class="w3-text-grey">Chiken wrap</p><br>
<p class="w3-text-grey">Pancakes</p><br>
<p class="w3-text-grey">Mashed potato</p><br>

<h5>Dessert</h5>

<p class="w3-text-grey">Pudding :Chocolate, Strawberry, Mango</p><br>
<p class="w3-text-grey">Apple Pie: Chocolate Pie, Strawberry Pie, Pineapple Pise</p><br>
<p class="w3-text-grey">Ice cream :Vanilla, Chocolate, strawberry</p><br>
<p class="w3-text-grey">Churros : Chocolate, tiramisu</p><br>
</div>

<div id="Minuman" class="w3-container menu w3-padding-48 w3-card">
<h5>Coffee</h5>
<p class="w3-text-grey">ice salted coffe</p><br>
<p class="w3-text-grey">Machiatto/conpanna</p><br>
<p class="w3-text-grey">Americano/ Long black</p><br>
<p class="w3-text-grey">Cappucino/ Latte</p><br>
<p class="w3-text-grey">Moccacino</p><br>
<p class="w3-text-grey">Solo Expresso</p><br>
<p class="w3-text-grey">Tiramisu Latte</p><br>

<h5>Chocolato</h5>
<p class="w3-text-grey">Chocolate espresso with milk</p><br>

<h5>Corretto</h5>
<p class="w3-text-grey">Whiskey and coffee</p><br>

<h5>tea</h5>
<p class="w3-text-grey">Hot/Cold</p><br>

<h5>Soda</h5>
<p class="w3-text-grey">Coca-Cola, Sprite, Fanta,dll</p>
</div> 
<img src="coffee-shop.jpg" style="width:100%;max-width:1000px;margin-top:32px;">
</div>
</div>

<!-- Contact/Area Container -->
<div class="w3-container" id="where" style="padding-bottom:32px;">
<div class="w3-content" style="max-width:700px">
<h5 class="w3-center w3-padding-48"><span class="w3-tag w3-wide">Dimana Kalian Dapat menemukan Kami</span></h5>
<p>Temukan Kami Diberbagai Cabang Outlet Kami.</p>
<img src="maps--1.jpg" class="w3-image" style="width:100%">
<p><span class="w3-tag">FYI!</span>Kami menawarkan katering layanan lengkap untuk acara apa pun, besar atau kecil. Kami memahami kebutuhan Anda dan kami akan menyediakan makanan untuk memenuhi kriteria terbesar dari semuanya, baik tampilan maupun rasanya.</p>
<p><strong>Reserve</strong> Pesan meja untuk hari spesial,bisa hubungi kami</p>
<form action="/action_page.php" target="_blank">
<p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Name" required name="Name"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="number" placeholder="How many people" required name="People"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="datetime-local" placeholder="Date and time" required name="date" value="2017-11-16T20:00"></p>
<p><input class="w3-input w3-padding-16 w3-border" type="text" placeholder="Message \ Special requirements" required name="Message"></p>
<p><button class="w3-button w3-black" type="submit">Kirim Pesan</button></p>
</form>
</div>
</div>

<!-- End page content -->
</div>

<!-- Footer -->
<footer class="w3-center w3-light-grey w3-padding-48 w3-large">
<p>@Caffe_kita <!--<a href="https://www.w3schools.com/w3css/default.asp" title="W3.CSS" target="_blank" class="w3-hover-text-green">w3.css</a>--></p>
</footer>

<script>
// Tabbed Menu
function openMenu(evt, menuName) {
var i, x, tablinks;
x = document.getElementsByClassName("menu");
for (i = 0; i < x.length; i++) {
x[i].style.display = "none";
}
tablinks = document.getElementsByClassName("tablink");
for (i = 0; i < x.length; i++) {
tablinks[i].className = tablinks[i].className.replace(" w3-dark-grey", "");
}
document.getElementById(menuName).style.display = "block";
evt.currentTarget.firstElementChild.className += " w3-dark-grey";
}
document.getElementById("myLink").click();
</script>

</body>
</html>
