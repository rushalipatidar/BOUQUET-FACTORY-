<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Bouquet Factory by Srishti</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#faf7ff;
color:#333;
}

header{
background:linear-gradient(135deg,#6a1b9a,#9c27b0);
padding:15px 8%;
display:flex;
justify-content:space-between;
align-items:center;
position:sticky;
top:0;
z-index:1000;
}

.logo{
display:flex;
align-items:center;
gap:15px;
color:white;
}

.logo img{
width:65px;
height:65px;
border-radius:50%;
background:white;
padding:5px;
}

nav a{
text-decoration:none;
color:white;
margin-left:20px;
font-weight:600;
}

.hero{
display:flex;
flex-wrap:wrap;
justify-content:center;
align-items:center;
padding:60px 8%;
background:white;
}

.hero-text{
flex:1;
min-width:300px;
}

.hero-text h1{
font-size:48px;
color:#6a1b9a;
}

.hero-text p{
margin:20px 0;
font-size:18px;
}

.btn{
display:inline-block;
padding:14px 28px;
background:#6a1b9a;
color:white;
text-decoration:none;
border-radius:30px;
}

.hero img{
width:350px;
max-width:100%;
border-radius:20px;
box-shadow:0 15px 35px rgba(0,0,0,.15);
}

section{
padding:70px 8%;
}

.section-title{
text-align:center;
font-size:34px;
color:#6a1b9a;
margin-bottom:40px;
}

.products{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:white;
border-radius:15px;
overflow:hidden;
box-shadow:0 10px 25px rgba(0,0,0,.08);
transition:.3s;
}

.card:hover{
transform:translateY(-10px);
}

.card img{
width:100%;
height:250px;
object-fit:cover;
}

.card h3{
padding:15px;
text-align:center;
}

.about{
text-align:center;
max-width:900px;
margin:auto;
font-size:18px;
line-height:30px;
}

.contact{
text-align:center;
}

.contact a{
display:inline-block;
margin:10px;
text-decoration:none;
padding:14px 25px;
border-radius:30px;
background:#6a1b9a;
color:white;
}

footer{
background:#6a1b9a;
color:white;
text-align:center;
padding:20px;
margin-top:40px;
}

.whatsapp{
position:fixed;
bottom:20px;
right:20px;
background:#25D366;
color:white;
padding:15px 20px;
border-radius:50px;
text-decoration:none;
font-weight:bold;
box-shadow:0 10px 20px rgba(0,0,0,.3);
}

</style>

</head>

<body>

<header>

<div class="logo">

<img src="logo.jpg">

<div>

<h2>Bouquet Factory</h2>

<small>by Srishti</small>

</div>

</div>

<nav>

<a href="#">Home</a>

<a href="#products">Products</a>

<a href="#about">About</a>

<a href="#contact">Contact</a>

</nav>

</header>

<section class="hero">

<div class="hero-text">

<h1>Handmade Resin Art & Personalized Gifts</h1>

<p>Beautiful handmade resin keychains, bouquets, frames and customized gifts made with love.</p>

<a href="https://wa.me/917898775838" class="btn">Order on WhatsApp</a>

</div>

<img src="product1.jpg">

</section>

<section id="products">

<h2 class="section-title">Our Products</h2>

<div class="products">

<div class="card">

<img src="product1.jpg">

<h3>Resin Photo Keychain</h3>

</div>

<div class="card">

<img src="product1.jpg">

<h3>Resin Frames</h3>

</div>

<div class="card">

<img src="product1.jpg">

<h3>Customized Bouquets</h3>

</div>

<div class="card">

<img src="product1.jpg">

<h3>Evil Eye Keychains</h3>

</div>

</div>

</section>

<section id="about">

<h2 class="section-title">About Us</h2>

<p class="about">

Welcome to <b>Bouquet Factory by Srishti</b>. We create premium handmade resin art, customized gifts, photo keychains, bouquets and unique creations specially designed for your loved ones.

</p>

</section>

<section id="contact">

<h2 class="section-title">Contact Us</h2>

<div class="contact">

<a href="tel:7898775838">📞 Call Now</a>

<a href="https://instagram.com/bouquet_factory_by_srishti">📷 Instagram</a>

</div>

</section>

<footer>

© 2026 Bouquet Factory by Srishti | All Rights Reserved

</footer>

<a class="whatsapp" href="https://wa.me/917898775838">

WhatsApp

</a>

</body>

</html>