# LANDING-PAGE-OF-MY-WEBSITE---MAINCRAFTS-TECHNOLOGY
MainCrafts Responsive Landing Page  The MainCrafts Responsive Landing Page is a modern and visually appealing website developed as part of a Full Stack Internship task. The project is designed to represent a startup, product, or digital service company through a professional and user-friendly interface.

<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>MainCrafts - Build Smarter</title>

<!-- Google Font -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;500;600;700;800&display=swap" rel="stylesheet">

<!-- Bootstrap -->
<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/css/bootstrap.min.css" rel="stylesheet">

<!-- Font Awesome -->
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css">

<style>

:root{
--primary:#4361ee;
--secondary:#7209b7;
--accent:#4cc9f0;
--dark:#0f172a;
--light:#f8fafc;
}

*{
margin:0;
padding:0;
box-sizing:border-box;
font-family:'Poppins',sans-serif;
scroll-behavior:smooth;
}

body{
background:#fff;
overflow-x:hidden;
}

/* Navbar */
.navbar{
background:#fff;
box-shadow:0 4px 15px rgba(0,0,0,0.08);
}

.navbar-brand{
font-size:30px;
font-weight:800;
color:var(--primary)!important;
}

.nav-link{
font-weight:500;
margin-left:15px;
transition:.3s;
}

.nav-link:hover{
color:var(--primary)!important;
}

/* Hero */
.hero{
min-height:100vh;
display:flex;
align-items:center;
justify-content:center;
text-align:center;
color:#fff;
background:linear-gradient(135deg,var(--primary),var(--secondary));
padding:100px 20px;
position:relative;
}

.hero::before{
content:'';
position:absolute;
width:300px;
height:300px;
background:rgba(255,255,255,.1);
border-radius:50%;
top:50px;
left:-100px;
}

.hero::after{
content:'';
position:absolute;
width:350px;
height:350px;
background:rgba(255,255,255,.08);
border-radius:50%;
bottom:-100px;
right:-100px;
}

.hero-content{
position:relative;
z-index:2;
}

.hero h1{
font-size:4rem;
font-weight:800;
margin-bottom:20px;
}

.hero p{
max-width:700px;
margin:auto;
font-size:1.2rem;
margin-bottom:30px;
}

.btn-main{
background:#fff;
color:var(--primary);
padding:14px 35px;
border-radius:50px;
font-weight:600;
text-decoration:none;
display:inline-block;
transition:.3s;
}

.btn-main:hover{
transform:translateY(-4px);
background:#f1f5f9;
}

/* Features */
.features{
padding:100px 0;
background:var(--light);
}

.section-title{
text-align:center;
margin-bottom:60px;
}

.section-title h2{
font-weight:700;
color:var(--dark);
}

.feature-card{
background:#fff;
padding:35px;
border-radius:20px;
text-align:center;
height:100%;
transition:.4s;
box-shadow:0 10px 25px rgba(0,0,0,.08);
}

.feature-card:hover{
transform:translateY(-10px);
}

.feature-card i{
font-size:50px;
margin-bottom:20px;
color:var(--primary);
}

.feature-card h4{
font-weight:600;
margin-bottom:15px;
}

/* Services */
.services{
padding:100px 0;
}

.service-box{
padding:30px;
border-radius:15px;
background:#fff;
box-shadow:0 5px 15px rgba(0,0,0,.08);
transition:.3s;
}

.service-box:hover{
transform:translateY(-8px);
}

.service-box i{
font-size:40px;
color:var(--secondary);
margin-bottom:15px;
}

/* Contact */
.contact{
padding:100px 0;
background:#f1f5f9;
}

.contact-card{
background:#fff;
padding:40px;
border-radius:20px;
box-shadow:0 5px 20px rgba(0,0,0,.08);
text-align:center;
}

/* Footer */
footer{
background:var(--dark);
color:#fff;
padding:30px 0;
text-align:center;
}

footer a{
color:var(--accent);
text-decoration:none;
margin:0 10px;
}

footer a:hover{
color:#fff;
}

/* Responsive */
@media(max-width:992px){

.hero h1{
font-size:3rem;
}

}

@media(max-width:768px){

.hero h1{
font-size:2.3rem;
}

.hero p{
font-size:1rem;
}

.nav-link{
margin-left:0;
}

}

</style>
</head>

<body>

<!-- Navbar -->
<nav class="navbar navbar-expand-lg sticky-top">
<div class="container">

<a class="navbar-brand" href="#">MainCrafts</a>

<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navMenu">
<span class="navbar-toggler-icon"></span>
</button>

<div class="collapse navbar-collapse" id="navMenu">

<ul class="navbar-nav ms-auto">

<li class="nav-item">
<a class="nav-link" href="#home">Home</a>
</li>

<li class="nav-item">
<a class="nav-link" href="#features">Features</a>
</li>

<li class="nav-item dropdown">
<a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown">
Services
</a>

<ul class="dropdown-menu">
<li><a class="dropdown-item" href="#">Web Development</a></li>
<li><a class="dropdown-item" href="#">App Development</a></li>
<li><a class="dropdown-item" href="#">UI/UX Design</a></li>
<li><a class="dropdown-item" href="#">Digital Marketing</a></li>
</ul>
</li>

<li class="nav-item">
<a class="nav-link" href="#contact">Contact</a>
</li>

</ul>

</div>
</div>
</nav>

<!-- Hero -->
<section class="hero" id="home">

<div class="hero-content">

<h1>Build Smarter with MainCrafts</h1>

<p>
Transform your ideas into powerful digital experiences.
We create modern websites, scalable applications,
and innovative solutions that help businesses grow faster.
</p>

<a href="#contact" class="btn-main">Get Started</a>

</div>

</section>

<!-- Features -->
<section class="features" id="features">

<div class="container">

<div class="section-title">
<h2>Our Features</h2>
<p>Everything you need to build and scale successfully.</p>
</div>

<div class="row g-4">

<div class="col-md-6 col-lg-3">
<div class="feature-card">
<i class="fas fa-bolt"></i>
<h4>Fast</h4>
<p>Optimized for high speed and smooth performance.</p>
</div>
</div>

<div class="col-md-6 col-lg-3">
<div class="feature-card">
<i class="fas fa-mobile-screen-button"></i>
<h4>Responsive</h4>
<p>Works perfectly on desktop, tablet and mobile.</p>
</div>
</div>

<div class="col-md-6 col-lg-3">
<div class="feature-card">
<i class="fas fa-chart-line"></i>
<h4>Scalable</h4>
<p>Grow your business without worrying about limits.</p>
</div>
</div>

<div class="col-md-6 col-lg-3">
<div class="feature-card">
<i class="fas fa-shield-halved"></i>
<h4>Secure</h4>
<p>Advanced protection and secure infrastructure.</p>
</div>
</div>

</div>

</div>

</section>

<!-- Services -->
<section class="services">

<div class="container">

<div class="section-title">
<h2>Services</h2>
<p>Solutions tailored to your business needs.</p>
</div>

<div class="row g-4">

<div class="col-md-4">
<div class="service-box">
<i class="fas fa-code"></i>
<h4>Web Development</h4>
<p>Modern, responsive and SEO-friendly websites.</p>
</div>
</div>

<div class="col-md-4">
<div class="service-box">
<i class="fas fa-laptop-code"></i>
<h4>UI/UX Design</h4>
<p>Beautiful interfaces focused on user experience.</p>
</div>
</div>

<div class="col-md-4">
<div class="service-box">
<i class="fas fa-bullhorn"></i>
<h4>Digital Marketing</h4>
<p>Boost your online presence and customer reach.</p>
</div>
</div>

</div>

</div>

</section>

<!-- Contact -->
<section class="contact" id="contact">

<div class="container">

<div class="contact-card">

<h2>Contact MainCrafts</h2>

<p class="mt-3">
<i class="fas fa-globe"></i>
www.maincrafts.com
</p>

<p>
<i class="fas fa-envelope"></i>
hr@maincrafts.com
</p>

<a href="mailto:hr@maincrafts.com" class="btn btn-primary mt-3">
Apply Now
</a>

</div>

</div>

</section>

<!-- Footer -->
<footer>

<p>Copyright © 2025 MainCrafts. All Rights Reserved.</p>

<p>
<a href="#">Privacy Policy</a> |
<a href="#">Terms</a> |
<a href="#contact">Contact</a>
</p>

</footer>

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.3/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
```

