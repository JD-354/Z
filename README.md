# 👟
<html><head><base href="javascript:void(0)" />

<meta charset="UTF-8">

<meta name="viewport" content="width=device-width, initial-scale=1.0">

<title>ZapatoStyle - Tu Tienda de Tenis</title>



<link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/css/bootstrap.min.css" rel="stylesheet">

<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.2/dist/js/bootstrap.bundle.min.js"></script>

<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.0.0/css/all.min.css">



<style>

:root {

--primary-blue: #1a75ff;

--secondary-blue: #e6f0ff;

}



body {

background: linear-gradient(135deg, var(--secondary-blue) 0%, white 100%); font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;

}



.navbar {

background-color: var(--primary-blue) !important;

}



.logo-container { display: flex;

align-items: center; gap: 10px;

}



.logo-text { color: white;

font-size: 24px; font-weight: bold;

}



.carousel-item img { height: 400px; object-fit: cover;

}



.product-card {

transition: transform 0.3s; background: white; border-radius: 10px;

 

box-shadow: 0 4px 8px rgba(0,0,0,0.1);

}



.product-card:hover { transform: translateY(-5px);

}



#cart-counter { position: relative; top: -10px;

right: -5px; background-color: red; color: white;

border-radius: 50%; padding: 2px 6px; font-size: 12px;

}



.footer {

background-color: var(--primary-blue); color: white;

padding: 20px 0; margin-top: 40px;

}

</style>

</head>

<body>



<!-- Navbar -->

<nav class="navbar navbar-expand-lg navbar-dark">

<div class="container">

<a class="navbar-brand" href="">

<div class="logo-container">

<svg width="40" height="40" viewBox="0 0 40 40">

<path d="M5 25 C5 20, 10 15, 20 15 C30 15, 35 20, 35 25 L35 30 L5 30 Z" fill="white"/>

<path d="M8 25 L32 25" stroke="var(--primary-blue)" stroke-width="2"/>

<path d="M10 20 C15 18, 25 18, 30 20" stroke="var(--primary-blue)" stroke-width="2" fill="none"/>

<path d="M15 20 L25 20 M15 22 L25 22" stroke="var(--primary-blue)" stroke-width="1"/>

</svg>

<span class="logo-text">Zapato J.A.N.P</span>

</div>

</a>



<button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">

<span class="navbar-toggler-icon"></span>

</button>

 

<div class="collapse navbar-collapse" id="navbarNav">

<ul class="navbar-nav me-auto">

<li class="nav-item">

<a class="nav-link" href="https://zapatostyle.com/inicio"><i class="fas fa-home"></i> Inicio</a>

</li>

<li class="nav-item">

<a class="nav-link" href="https://jd-354.github.io/S/"><i class="fas fa-info-circle"></i> Sobre

Nosotros</a>

</li>

<li class="nav-item">

<a   class="nav-link"   href="https://zapatostyle.com/contacto"><i   class="fas   fa-envelope"></i>

Contacto</a>

</li>

</ul>



<form class="d-flex me-3">

<input class="form-control me-2" type="search" placeholder="Buscar zapatos...">

<button class="btn btn-outline-light" type="submit"><i class="fas fa-search"></i></button>

</form>



<div class="cart-container">

<button class="btn btn-outline-light">

<i class="fas fa-shopping-cart"></i>

<span id="cart-counter">0</span>

</button>

</div>

</div>

</div>

</nav>



<!-- Carousel -->

<div id="mainCarousel" class="carousel slide mb-4" data-bs-ride="carousel">

<div class="carousel-indicators">

<button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="0" class="active"></button>

<button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="1"></button>

<button type="button" data-bs-target="#mainCarousel" data-bs-slide-to="2"></button>

</div>

<div class="carousel-inner">

<div class="carousel-item active">

<img src="https://images.unsplash.com/photo-1552346154-21d32810aba3" class="d-block w-100" alt="Jordan sneakers collection, professional product photography" height="400">
</div>

<div class="carousel-caption">

<h3>Colección Jordan</h3>

<p>Descubre la legendaria línea de Jordan</p>

 

</div>

<div class="carousel-item">

<img src="https://images.unsplash.com/photo-1542291026-7eec264c27ff" class="d-block w-100" alt="Nike running shoes lineup, studio lighting" height="400">

<div class="carousel-caption">

<h3>Nike Innovation</h3>

<p>Tecnología y estilo en cada paso</p>

</div>

</div>

<div class="carousel-item">

<img src="https://images.unsplash.com/photo-1518002171953-a080ee817e1f" class="d-block w-100" alt="Adidas sports collection, lifestyle photography" height="400">

<div class="carousel-caption">

<h3>Adidas Originals</h3>

<p>El estilo clásico reinventado</p>

</div>

</div>

</div>

<button class="carousel-control-prev" type="button" data-bs-target="#mainCarousel" data-bs-slide="prev">

<span class="carousel-control-prev-icon"></span>

</button>

<button class="carousel-control-next" type="button" data-bs-target="#mainCarousel" data-bs-slide="next">

<span class="carousel-control-next-icon"></span>

</button>

</div>


<!-- Productos -->

<div class="container mb-5">

<h2 class="text-center mb-4">Nuestras Colecciones</h2>



<div class="row g-4">

<!-- Jordan -->

<div class="col-md-3">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1586525198428-225f6f12cff5" alt="Air Jordan 1 Retro High, product shot" class="img-fluid mb-3" height="200">

<h5>Jordan Collection</h5>

<p>29 modelos disponibles</p>
<a href="https://jd-354.github.io/Jor/">
<button class="btn btn-primary w-100">Ver Colección </button>
</a>
</div>

</div>



<!-- Nike -->

<div class="col-md-3">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1605348532760-6753d2c43329" alt="Nike Air Max, lifestyle

 

photo" class="img-fluid mb-3" height="200">

<h5>Nike Collection</h5>

<p>30 modelos disponibles</p>
<a href="https://jd-354.github.io/Nk/">
<button class="btn btn-primary w-100">Ver Colección</button>
</a>
</div>

</div>



<!-- Puma -->

<div class="col-md-3">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1608231387042-66d1773070a5" alt="Puma RS-X, product photography" class="img-fluid mb-3" height="200">

<h5>Puma Collection</h5>

<p>20 modelos disponibles</p>
<a href="https://jd-354.github.io/Pum/">
<button class="btn btn-primary w-100">Ver Colección</button>
</a>
</div>

</div>



<!-- Adidas -->

<div class="col-md-3">

<div class="product-card p-3">

<img src="https://images.unsplash.com/photo-1582588678413-dbf45f4823e9" alt="Adidas Ultraboost, studio shot" class="img-fluid mb-3" height="200">

<h5>Adidas Collection</h5>

<p>30 modelos disponibles</p>
<a href="https://jd-354.github.io/AD/">
<button class="btn btn-primary w-100">Ver Colección</button>
</a>
</div>

</div>

</div>

</div>



<!-- Footer -->

<footer class="footer">

<div class="container">

<div class="row">

<div class="col-md-4">

<h5>Contacto</h5>

<p><i class="fas fa-phone"></i> +1 234 567 890</p>

<p><i class="fas fa-envelope"></i> info@zapatostyle.com</p>

</div>

<div class="col-md-4">

<h5>Síguenos</h5>

<a href="https://facebook.com" class="text-white me-3"><i class="fab fa-facebook"></i></a>

<a href="https://instagram.com" class="text-white me-3"><i class="fab fa-instagram"></i></a>

<a href="https://twitter.com" class="text-white"><i class="fab fa-twitter"></i></a>

 

<div class="col-md-4">

<h5>Newsletter</h5>

<form class="d-flex">

<input type="email" class="form-control me-2" placeholder="Tu email">

<button class="btn btn-outline-light">Suscribir</button>

</form>

</div>

</div>

</div>





<script>

let cartCount = 0;



document.querySelectorAll('.btn-primary').forEach(button => { button.addEventListener('click', () => {

cartCount++;

document.getElementById('cart-counter').textContent = cartCount;



// Animación del contador

const counter = document.getElementById('cart-counter'); counter.style.transform = 'scale(1.5)';

setTimeout(() => { counter.style.transform = 'scale(1)';

}, 200);

});

});

</script>





