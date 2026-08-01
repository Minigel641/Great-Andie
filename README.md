<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Andies Glow Hub | Skincare Portfolio</title>

<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700&display=swap" rel="stylesheet">

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family:'Poppins',sans-serif;
}

html{
    scroll-behavior:smooth;
}

body{
    background:#faf8f7;
    color:#333;
    line-height:1.7;
}

/* Header */

header{
    position:fixed;
    top:0;
    width:100%;
    background:#fff;
    box-shadow:0 2px 15px rgba(0,0,0,0.08);
    z-index:1000;
}

nav{
    max-width:1200px;
    margin:auto;
    display:flex;
    justify-content:space-between;
    align-items:center;
    padding:18px 30px;
}

.logo{
    font-size:1.8rem;
    font-weight:700;
    color:#d17a98;
}

nav ul{
    display:flex;
    list-style:none;
    gap:25px;
}

nav ul li a{
    text-decoration:none;
    color:#444;
    font-weight:500;
    transition:0.3s;
}

nav ul li a:hover{
    color:#d17a98;
}

/* Hero Section */

.hero{
    min-height:100vh;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    padding:100px 20px;
    background:
    linear-gradient(
    rgba(255,255,255,0.75),
    rgba(255,255,255,0.85)),
    url('https://images.unsplash.com/photo-1522335789203-aabd1fc54bc9?auto=format&fit=crop&w=1400&q=80');

    background-size:cover;
    background-position:center;
}

.hero-content{
    max-width:800px;
}

.hero h1{
    font-size:3.5rem;
    color:#a75473;
    margin-bottom:15px;
}

.hero h2{
    color:#666;
    margin-bottom:20px;
}

.hero p{
    margin-bottom:30px;
    font-size:1.1rem;
}

.btn{
    display:inline-block;
    background:#d17a98;
    color:white;
    text-decoration:none;
    padding:14px 30px;
    border-radius:40px;
    font-weight:600;
    transition:0.3s;
}

.btn:hover{
    background:#b75f80;
}

/* General */

section{
    padding:90px 20px;
}

.container{
    max-width:1200px;
    margin:auto;
}

.section-title{
    text-align:center;
    margin-bottom:50px;
}

.section-title h2{
    color:#a75473;
    font-size:2.2rem;
}

/* About */

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:50px;
    align-items:center;
}

.profile-image{
    width:100%;
    max-width:450px;
    height:550px;
    object-fit:cover;
    border-radius:25px;
    box-shadow:0 15px 35px rgba(0,0,0,0.15);
}

.founder-name{
    color:#d17a98;
    font-size:2rem;
    margin-bottom:15px;
}

/* Services */

.cards{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:20px;
    box-shadow:0 5px 20px rgba(0,0,0,0.08);
    transition:0.3s;
}

.card:hover{
    transform:translateY(-8px);
}

.card h3{
    color:#d17a98;
    margin-bottom:10px;
}

/* Products */

.products{
    background:#fff4f8;
}

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:280px;
    object-fit:cover;
    border-radius:20px;
}

/* Stats */

.stats{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(220px,1fr));
    gap:20px;
}

.stat{
    background:#d17a98;
    color:white;
    text-align:center;
    padding:30px;
    border-radius:20px;
}

.stat h3{
    font-size:2rem;
}

/* Contact */

.contact{
    text-align:center;
}

.contact-box{
    background:white;
    max-width:700px;
    margin:auto;
    padding:40px;
    border-radius:25px;
    box-shadow:0 5px 20px rgba(0,0,0,0.08);
}

.contact-box p{
    margin-bottom:12px;
}

.social-links{
    margin-top:20px;
}

.social-links a{
    display:inline-block;
    margin:10px;
    text-decoration:none;
    color:#d17a98;
    font-weight:600;
}

/* Footer */

footer{
    background:#222;
    color:white;
    text-align:center;
    padding:25px;
}

/* Mobile */

@media(max-width:768px){

    nav ul{
        display:none;
    }

    .hero h1{
        font-size:2.4rem;
    }

    .about{
        grid-template-columns:1fr;
    }

    .profile-image{
        height:auto;
    }
}

</style>
</head>

<body>

<header>
<nav>

<div class="logo">Andies Glow Hub</div>

<ul>
<li><a href="#about">About</a></li>
<li><a href="#services">Services</a></li>
<li><a href="#products">Products</a></li>
<li><a href="#contact">Contact</a></li>
</ul>

</nav>
</header>

<!-- HERO SECTION -->

<section class="hero">

<div class="hero-content">

<h1>Andies Glow Hub</h1>

<h2>Premium Skincare Products & Beauty Solutions</h2>

<p>
Helping clients achieve healthy, radiant and glowing skin through
authentic skincare products, personalized recommendations, and expert
beauty guidance.
</p>

<a href="#contact" class="btn">Shop With Us</a>

</div>

</section>

<!-- ABOUT SECTION -->

<section id="about">

<div class="container">

<div class="section-title">
<h2>Meet The Founder</h2>
</div>

<div class="about">

<img src="471906.jpg" alt="Angel Odoh" class="profile-image">

<div>

<h3 class="founder-name">Angel Odoh</h3>

<p>
Hello and welcome to Andies Glow Hub. I am passionate about helping
people achieve healthy, glowing, and confident skin through carefully
selected skincare products and professional skincare guidance.
</p>

<br>

<p>
At Andies Glow Hub, we believe that skincare should be simple,
effective, and accessible. Every product we offer is chosen with
quality, safety, and visible results in mind.
</p>

<br>

<a href="#contact" class="btn">Contact Me</a>

</div>

</div>

</div>

</section>

<!-- SERVICES -->

<section id="services">

<div class="container">

<div class="section-title">
<h2>Our Services</h2>
</div>

<div class="cards">

<div class="card">
<h3>Skin Consultation</h3>
<p>Personalized skincare advice based on your skin type and concerns.</p>
</div>

<div class="card">
<h3>Authentic Products</h3>
<p>Quality skincare products sourced from trusted brands.</p>
</div>

<div class="card">
<h3>Routine Planning</h3>
<p>Customized skincare routines for better and lasting results.</p>
</div>

<div class="card">
<h3>Customer Support</h3>
<p>Continuous support throughout your skincare journey.</p>
</div>

</div>

</div>

</section>

<!-- PRODUCTS -->

<section id="products" class="products">

<div class="container">

<div class="section-title">
<h2>Featured Products</h2>
</div>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1620916566398-39f1143ab7be?auto=format&fit=crop&w=800&q=80" alt="Serum">

<img src="https://images.unsplash.com/photo-1556228578-8c89e6adf883?auto=format&fit=crop&w=800&q=80" alt="Moisturizer">

<img src="https://images.unsplash.com/photo-1596755389378-c31d21fd1273?auto=format&fit=crop&w=800&q=80" alt="Cleanser">

<img src="https://images.unsplash.com/photo-1601049541289-9b1b7bbbfe19?auto=format&fit=crop&w=800&q=80" alt="Sunscreen">

</div>

</div>

</section>

<!-- BUSINESS HIGHLIGHTS -->

<section>

<div class="container">

<div class="section-title">
<h2>Business Highlights</h2>
</div>

<div class="stats">

<div class="stat">
<h3>500+</h3>
<p>Happy Clients</p>
</div>

<div class="stat">
<h3>100+</h3>
<p>Products Sold</p>
</div>

<div class="stat">
<h3>98%</h3>
<p>Customer Satisfaction</p>
</div>

<div class="stat">
<h3>5★</h3>
<p>Average Rating</p>
</div>

</div>

</div>

</section>

<!-- CONTACT -->

<section id="contact">

<div class="container">

<div class="section-title">
<h2>Contact Andies Glow Hub</h2>
</div>

<div class="contact-box">

<p><strong>Founder:</strong> Angel Odoh</p>

<p><strong>Brand Name:</strong> Andies Glow Hub</p>

<p><strong>Email:</strong> angelhandie072@gmail.com</p>

<p><strong>WhatsApp:</strong> 07035566442</p>

<p><strong>Instagram:</strong> @angel_andies</p>

<p><strong>Facebook:</strong> Angel Andie</p>

<p><strong>TikTok:</strong> @prettyandie77</p>

<div class="social-links">

<a href="mailto:angelhandie072@gmail.com">Email Me</a>

<a href="https://wa.me/2347035566442">WhatsApp</a>

</div>

</div>

</div>

</section>

<!-- FOOTER -->

<footer>

<p id="footer-text"></p>

<p style="margin-top:10px;">
Andies Glow Hub • Founded by Angel Odoh
</p>

</footer>

<script>

const year = new Date().getFullYear();

document.getElementById("footer-text").innerHTML =
`© ${year} Andies Glow Hub. All Rights Reserved.`;

console.log("Andies Glow Hub Website Loaded Successfully");

</script>

</body>
</html>
