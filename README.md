<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Saurabh Restaurant</title>

<style>

body{
margin:0;
font-family:Arial;
background:#f4f4f4;
}

header{
background:#111;
color:white;
padding:20px;
text-align:center;
}

nav{
background:#333;
padding:10px;
text-align:center;
}

nav a{
color:white;
margin:10px;
text-decoration:none;
font-size:18px;
}

.hero{
background:url("https://images.unsplash.com/photo-1504674900247-0877df9cc836");
background-size:cover;
height:300px;
display:flex;
align-items:center;
justify-content:center;
color:white;
font-size:40px;
font-weight:bold;
}

.menu{
padding:40px;
text-align:center;
}

.menu h2{
margin-bottom:20px;
}

.menu-items{
display:flex;
justify-content:center;
gap:30px;
flex-wrap:wrap;
}

.item{
background:white;
padding:20px;
border-radius:10px;
width:200px;
box-shadow:0 0 10px rgba(0,0,0,0.1);
}

.contact{
background:#222;
color:white;
padding:40px;
text-align:center;
}

input,textarea{
width:80%;
padding:10px;
margin:10px;
border:none;
border-radius:5px;
}

button{
padding:10px 20px;
background:red;
color:white;
border:none;
cursor:pointer;
}

footer{
background:black;
color:white;
text-align:center;
padding:10px;
}

</style>
</head>

<body>

<header>
<h1>Saurabh Restaurant</h1>
<p>Best Food in Town</p>
</header>

<nav>
<a href="#">Home</a>
<a href="#">Menu</a>
<a href="#">Contact</a>
</nav>

<div class="hero">
Delicious Food
</div>

<section class="menu">

<h2>Our Menu</h2>

<div class="menu-items">

<div class="item">
<h3>Pizza</h3>
<p>₹199</p>
</div>

<div class="item">
<h3>Burger</h3>
<p>₹149</p>
</div>

<div class="item">
<h3>Pasta</h3>
<p>₹179</p>
</div>

<div class="item">
<h3>Cold Drink</h3>
<p>₹59</p>
</div>

</div>

</section>

<section class="contact">

<h2>Contact Us</h2>

<input type="text" placeholder="Your Name"><br>

<input type="email" placeholder="Your Email"><br>

<textarea placeholder="Message"></textarea><br>

<button>Send Message</button>

</section>

<footer>

<p>© 2026 Saurabh Restaurant</p>

</footer>

</body>
</html>
