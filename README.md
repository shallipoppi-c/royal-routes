<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>Royal Routes Tours & Travel</title>

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:Arial, sans-serif;
}

body{
background:#f5f5f5;
color:#333;
}

header{
background:url('https://images.unsplash.com/photo-1507525428034-b723cf961d3e');
background-size:cover;
background-position:center;
height:90vh;
color:white;
display:flex;
justify-content:center;
align-items:center;
text-align:center;
}

.overlay{
background:rgba(0,0,0,0.6);
padding:40px;
border-radius:10px;
}

.overlay h1{
font-size:50px;
margin-bottom:20px;
}

.overlay p{
font-size:20px;
margin-bottom:20px;
}

.btn{
display:inline-block;
padding:12px 25px;
background:#ff9800;
color:white;
text-decoration:none;
border-radius:5px;
font-weight:bold;
}

nav{
background:#000;
padding:15px;
text-align:center;
position:sticky;
top:0;
}

nav a{
color:white;
margin:15px;
text-decoration:none;
font-weight:bold;
}

section{
padding:60px 20px;
text-align:center;
}

.cards{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:20px;
margin-top:30px;
}

.card{
background:white;
border-radius:10px;
overflow:hidden;
box-shadow:0 4px 10px rgba(0,0,0,0.1);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card h3{
padding:15px;
}

.card p{
padding:0 15px 20px;
}

.contact{
background:#0b3d91;
color:white;
}

footer{
background:black;
color:white;
text-align:center;
padding:20px;
}

</style>
</head>

<body>

<nav>
<a href="#">Home</a>
<a href="#destinations">Destinations</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

<header>
<div class="overlay">
<h1>Royal Routes Tours & Travel</h1>
<p>Explore Kenya & Beyond With Comfort</p>

<a class="btn" href="https://wa.me/254715531301">
Book Now
</a>
</div>
</header>

<section id="destinations">

<h2>Popular Destinations</h2>

<div class="cards">

<div class="card">
<img src="https://images.unsplash.com/photo-1516026672322-bc52d61a55d5">
<h3>Diani Beach</h3>
<p>Relax at Kenya’s beautiful coast.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1501785888041-af3ef285b470">
<h3>Maasai Mara</h3>
<p>Experience wildlife and adventure.</p>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1493246507139-91e8fad9978e">
<h3>Mount Kenya</h3>
<p>Enjoy hiking and nature views.</p>
</div>

</div>

</section>

<section id="about">

<h2>Why Choose Us?</h2>

<p>
Royal Routes offers affordable travel packages,
holiday trips, hotel bookings and tour adventures
across Kenya and beyond.
</p>

</section>

<section class="contact" id="contact">

<h2>Contact Us</h2>

<p>Phone: 0715531301</p>

<p>Email: royalroutes@gmail.com</p>

<br>

<a class="btn" href="https://wa.me/254715531301">
Chat on WhatsApp
</a>

</section>

<footer>
<p>Royal Routes Tours & Travel © 2026</p>
</footer>

</body>
</html>
