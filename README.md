<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>We-Go Catering Services</title>

<style>

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
    font-family: Arial, Helvetica, sans-serif;
}

body{
    background:#f8f8f8;
    color:#333;
    scroll-behavior:smooth;
}

/* HEADER */

header{
    width:100%;
    background:#14532d;
    padding:18px 8%;
    display:flex;
    justify-content:space-between;
    align-items:center;
    position:fixed;
    top:0;
    z-index:1000;
}

.logo{
    color:#ffd54f;
    font-size:32px;
    font-weight:bold;
}

.logo span{
    color:white;
}

nav a{
    text-decoration:none;
    color:white;
    margin-left:25px;
    font-weight:bold;
    transition:0.3s;
}

nav a:hover{
    color:#ffd54f;
}

/* HERO SECTION */

.hero{
    height:100vh;
    background:
    linear-gradient(rgba(0,0,0,0.6), rgba(0,0,0,0.6)),
    url('https://images.unsplash.com/photo-1555244162-803834f70033?q=80&w=1600&auto=format&fit=crop');
    background-size:cover;
    background-position:center;
    display:flex;
    justify-content:center;
    align-items:center;
    text-align:center;
    color:white;
    padding:20px;
}

.hero-content h1{
    font-size:70px;
    margin-bottom:20px;
}

.hero-content p{
    font-size:22px;
    max-width:800px;
    margin:auto;
    line-height:1.6;
}

.btn{
    display:inline-block;
    margin-top:30px;
    padding:15px 35px;
    background:#ffd54f;
    color:#14532d;
    text-decoration:none;
    font-weight:bold;
    border-radius:30px;
    transition:0.3s;
}

.btn:hover{
    background:white;
}

/* GENERAL SECTIONS */

section{
    padding:90px 8%;
}

.section-title{
    text-align:center;
    font-size:42px;
    color:#14532d;
    margin-bottom:50px;
}

/* ABOUT */

.about{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:40px;
    align-items:center;
}

.about img{
    width:100%;
    border-radius:15px;
    box-shadow:0 5px 15px rgba(0,0,0,0.2);
}

.about-text h3{
    color:#14532d;
    font-size:28px;
    margin-bottom:20px;
}

.about-text p{
    line-height:1.8;
    margin-bottom:20px;
}

/* SERVICES */

.services{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
    gap:25px;
}

.card{
    background:white;
    padding:30px;
    border-radius:15px;
    text-align:center;
    transition:0.3s;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
}

.card:hover{
    transform:translateY(-10px);
}

.card h3{
    color:#14532d;
    margin-bottom:15px;
    font-size:24px;
}

.card p{
    line-height:1.6;
}

/* COLLABORATIONS */

.collab{
    background:#14532d;
    color:white;
    border-radius:20px;
    text-align:center;
    padding:60px 30px;
}

.collab h2{
    font-size:40px;
    margin-bottom:20px;
}

.collab p{
    max-width:800px;
    margin:auto;
    line-height:1.8;
    font-size:18px;
}

/* GALLERY */

.gallery{
    display:grid;
    grid-template-columns:repeat(auto-fit, minmax(250px,1fr));
    gap:20px;
}

.gallery img{
    width:100%;
    height:250px;
    object-fit:cover;
    border-radius:15px;
    transition:0.3s;
}

.gallery img:hover{
    transform:scale(1.03);
}

/* CONTACT */

.contact{
    text-align:center;
}

.contact-box{
    background:white;
    padding:50px;
    border-radius:20px;
    box-shadow:0 5px 15px rgba(0,0,0,0.1);
    max-width:700px;
    margin:auto;
}

.contact-box h3{
    color:#14532d;
    margin-bottom:20px;
    font-size:30px;
}

.contact-box p{
    margin:10px 0;
    font-size:18px;
}

/* FOOTER */

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:25px;
    margin-top:40px;
}

/* RESPONSIVE */

@media(max-width:768px){

    .hero-content h1{
        font-size:45px;
    }

    .hero-content p{
        font-size:18px;
    }

    .about{
        grid-template-columns:1fr;
    }

    nav{
        display:none;
    }
}

</style>
</head>

<body>

<!-- HEADER -->

<header>

<div class="logo">WE-GO <span>Catering</span></div>

<nav>
<a href="#home">Home</a>
<a href="#about">About</a>
<a href="#services">Services</a>
<a href="#gallery">Gallery</a>
<a href="#contact">Contact</a>
</nav>

</header>

<!-- HERO -->

<section class="hero" id="home">

<div class="hero-content">

<h1>We-Go Catering Services</h1>

<p>
Premium Catering Services at Affordable Rates —
Customized to Your Preferences with Elegant Food Presentation,
Exceptional Service, and Wide Collaborative Event Packages.
</p>

<a href="#contact" class="btn">Book Your Event</a>

</div>

</section>

<!-- ABOUT -->

<section id="about">

<h2 class="section-title">About Us</h2>

<div class="about">

<img src="https://images.unsplash.com/photo-1466978913421-dad2ebd01d17?q=80&w=1200&auto=format&fit=crop">

<div class="about-text">

<h3>Elegant Catering Made Affordable</h3>

<p>
At <strong>We-Go Catering Services</strong>, we believe that every celebration deserves premium-quality food and excellent service without expensive pricing.
</p>

<p>
We provide fully customizable catering packages tailored to your style, theme, taste, and budget. Whether it's an intimate family gathering or a grand corporate event, our team is ready to deliver unforgettable dining experiences.
</p>

<p>
We also collaborate with decorators, event organizers, photographers, churches, schools, and corporate partners to make your event complete and stress-free.
</p>

</div>

</div>

</section>

<!-- SERVICES -->

<section id="services">

<h2 class="section-title">Our Services</h2>

<div class="services">

<div class="card">
<h3>Wedding Catering</h3>
<p>
Elegant buffet setups and premium menus for your special day.
</p>
</div>

<div class="card">
<h3>Birthday Parties</h3>
<p>
Affordable catering packages for kids, adults, and themed parties.
</p>
</div>

<div class="card">
<h3>Corporate Events</h3>
<p>
Professional catering services for meetings, seminars, and conferences.
</p>
</div>

<div class="card">
<h3>Customized Menus</h3>
<p>
Choose your preferred dishes and create your own catering experience.
</p>
</div>

<div class="card">
<h3>Food Tray Packages</h3>
<p>
Perfect for family gatherings, office events, and celebrations.
</p>
</div>

<div class="card">
<h3>Event Collaborations</h3>
<p>
Partnering with decorators, coordinators, and event suppliers.
</p>
</div>

</div>

</section>

<!-- COLLABORATIONS -->

<section>

<div class="collab">

<h2>Wide Range of Collaborations</h2>

<p>
We-Go Catering Services proudly works with event coordinators,
churches, schools, businesses, photographers, and party organizers
to create seamless and memorable celebrations.
Our collaborations help us deliver complete event experiences tailored to your vision.
</p>

</div>

</section>

<!-- GALLERY -->

<section id="gallery">

<h2 class="section-title">Food Gallery</h2>

<div class="gallery">

<img src="https://images.unsplash.com/photo-1544025162-d76694265947?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1504674900247-0877df9cc836?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1551218808-94e220e084d2?q=80&w=1200&auto=format&fit=crop">

<img src="https://images.unsplash.com/photo-1517248135467-4c7edcad34c4?q=80&w=1200&auto=format&fit=crop">

</div>

</section>

<!-- CONTACT -->

<section id="contact" class="contact">

<h2 class="section-title">Contact Us</h2>

<div class="contact-box">

<h3>Let's Plan Your Event</h3>

<p><strong>Phone:</strong> +63 912 345 6789</p>

<p><strong>Email:</strong> wegocatering@gmail.com</p>

<p><strong>Facebook:</strong> We-Go Catering Services</p>

<p><strong>Location:</strong> Philippines</p>

<a href="#" class="btn">Send Inquiry</a>

</div>

</section>

<!-- FOOTER -->

<footer>

<p>
© 2026 We-Go Catering Services | Premium Catering at Affordable Rates
</p>

</footer>

</body>
</html>
