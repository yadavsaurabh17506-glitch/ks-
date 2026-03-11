<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Royal Taste Restaurant</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&display=swap" rel="stylesheet">

<style>

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
}

body{
background:#111;
color:white;
}

/* HEADER */

header{
display:flex;
justify-content:space-between;
align-items:center;
padding:20px 10%;
background:#000;
position:sticky;
top:0;
}

.logo{
font-size:24px;
color:#ffb400;
font-weight:600;
}

nav a{
margin-left:20px;
text-decoration:none;
color:white;
font-weight:500;
transition:0.3s;
}

nav a:hover{
color:#ffb400;
}

/* HERO */

.hero{
height:90vh;
display:flex;
justify-content:center;
align-items:center;
flex-direction:column;
text-align:center;
background:url("https://images.unsplash.com/photo-1504674900247-0877df9cc836") center/cover;
}

.hero h1{
font-size:60px;
margin-bottom:10px;
}

.hero p{
font-size:20px;
margin-bottom:20px;
}

.hero button{
padding:12px 30px;
background:#ffb400;
border:none;
font-size:16px;
cursor:pointer;
border-radius:5px;
}

/* MENU */

.menu{
padding:80px 10%;
text-align:center;
background:#1b1b1b;
}

.menu h2{
font-size:40px;
margin-bottom:40px;
}

.menu-container{
display:grid;
grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
gap:25px;
}

.card{
background:#222;
border-radius:10px;
overflow:hidden;
transition:0.3s;
}

.card:hover{
transform:scale(1.05);
}

.card img{
width:100%;
height:200px;
object-fit:cover;
}

.card-content{
padding:20px;
}

.price{
color:#ffb400;
margin-top:10px;
font-weight:bold;
}

/* ABOUT */

.about{
padding:80px 10%;
display:flex;
flex-wrap:wrap;
align-items:center;
gap:40px;
}

.about img{
width:400px;
border-radius:10px;
}

.about-text{
max-width:500px;
}

/* CONTACT */

.contact{
padding:80px 10%;
background:#1b1b1b;
text-align:center;
}

form{
max-width:500px;
margin:auto;
display:flex;
flex-direction:column;
}

input,textarea{
padding:12px;
margin:10px 0;
border:none;
border-radius:5px;
}

button{
padding:12px;
background:#ffb400;
border:none;
cursor:pointer;
font-size:16px;
}

/* FOOTER */

footer{
text-align:center;
padding:20px;
background:black;
margin-top:30px;
}

</style>
</head>

<body>

<header>

<div class="logo">Royal Taste</div>

<nav>
<a href="#">Home</a>
<a href="#menu">Menu</a>
<a href="#about">About</a>
<a href="#contact">Contact</a>
</nav>

</header>

<section class="hero">

<h1>Welcome to Royal Taste</h1>
<p>Experience the best food in town</p>
<button>View Menu</button>

</section>

<section class="menu" id="menu">

<h2>Our Special Menu</h2>

<div class="menu-container">

<div class="card">
<img src="https://images.unsplash.com/photo-1594007654729-407eedc4fe24">
<div class="card-content">
<h3>Cheese Pizza</h3>
<p>Fresh cheesy pizza with toppings</p>
<div class="price">₹299</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1550547660-d9450f859349">
<div class="card-content">
<h3>Classic Burger</h3>
<p>Juicy grilled burger</p>
<div class="price">₹199</div>
</div>
</div>

<div class="card">
<img src="https://images.unsplash.com/photo-1525755662778-989d0524087e">
<div class="card-content">
<h3>Italian Pasta</h3>
<p>Creamy white sauce pasta</p>
<div class="price">₹249</div>
</div>
</div>

</div>

</section>

<section class="about" id="about">

<img src="https://images.unsplash.com/photo-1555396273-367ea4eb4db5">

<div class="about-text">

<h2>About Our Restaurant</h2>

<p>
Royal Taste is one of the best restaurants offering
fresh and delicious food. Our chefs prepare every
dish with passion and high-quality ingredients.
</p>

</div>

</section>

<section class="contact" id="contact">

<h2>Contact Us</h2>

<form id="contactForm">

<input type="text" placeholder="Your Name" required>

<input type="email" placeholder="Your Email" required>

<textarea placeholder="Your Message" rows="4"></textarea>

<button type="submit">Send Message</button>

</form>

</section>

<footer>

<p>© 2026 Royal Taste Restaurant</p>

</footer>

<script>

document.getElementById("contactForm").addEventListener("submit",function(e){

e.preventDefault();

alert("Message Sent Successfully!");

});

</script>

</body>
</html>
