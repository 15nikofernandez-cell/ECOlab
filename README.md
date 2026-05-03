<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>ECOLAB</title>

<style>
body {
  margin:0;
  font-family: Arial, sans-serif;
  background:#f5f5f5;
}

header {
  background:#0f3d3e;
  color:white;
  padding:20px;
  text-align:center;
}

nav {
  background:#0c2f30;
  padding:10px;
  text-align:center;
}

nav a {
  color:white;
  margin:0 15px;
  text-decoration:none;
}

.hero {
  display:flex;
  align-items:center;
  justify-content:space-between;
  padding:40px;
  background:white;
}

.hero img {
  width:300px;
}

.hero-text {
  max-width:500px;
}

.btn {
  background:#0f3d3e;
  color:white;
  padding:10px 20px;
  display:inline-block;
  margin-top:15px;
  text-decoration:none;
}

.products {
  padding:40px;
  text-align:center;
}

.grid {
  display:flex;
  gap:20px;
  flex-wrap:wrap;
  justify-content:center;
}

.card {
  background:white;
  padding:20px;
  width:200px;
  border-radius:10px;
}

footer {
  background:#0f3d3e;
  color:white;
  text-align:center;
  padding:20px;
}
</style>
</head>

<body>

<header>
<h1>ECOLAB</h1>
<p>Imprime el cambio</p>
</header>

<nav>
<a href="#">Inicio</a>
<a href="#">Productos</a>
<a href="#">Sostenibilidad</a>
<a href="#">Contacto</a>
</nav>

<section class="hero">
<div class="hero-text">
<h2>Tinta hecha con hollín reciclado</h2>
<p>Convertimos residuos en tinta de alta calidad para un futuro sostenible.</p>
<a class="btn">Comprar ahora</a>
</div>
<img src="https://via.placeholder.com/300" alt="producto">
</section>

<section class="products">
<h2>Productos</h2>

<div class="grid">

<div class="card">
<h3>Tinta ECOLAB</h3>
<p>Alta calidad</p>
<p><strong>24,90 €</strong></p>
</div>

<div class="card">
<h3>Pulsera ECOLAB</h3>
<p>Material reciclado</p>
<p><strong>4,90 €</strong></p>
</div>

<div class="card">
<h3>Termo ECOLAB</h3>
<p>Acero inoxidable</p>
<p><strong>24,90 €</strong></p>
</div>

<div class="card">
<h3>Taza ECOLAB</h3>
<p>Eco-friendly</p>
<p><strong>14,90 €</strong></p>
</div>

</div>
</section>

<footer>
<p>© 2026 ECOLAB - Innovación sostenible</p>
</footer>

</body>
</html>
