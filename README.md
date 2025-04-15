<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Consultora Digital Matías Núñez</title>
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/css/bootstrap.min.css" rel="stylesheet">
  <style>
    .hero {
      background-image: url('https://picsum.photos/seed/hero/1200/400');
      background-size: cover;
      background-position: center;
      padding: 100px 0;
      color: white;
      text-align: center;
    }
    .card {
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    #contacto {
      background-color: #f8f9fa;
      padding: 60px 0;
    }
  </style>
</head>
<body>

<!-- NAVBAR -->
<nav class="navbar navbar-expand-lg navbar-dark bg-dark">
  <div class="container">
    <a class="navbar-brand" href="#">Consultora Digital</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarNav">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav ms-auto">
        <li class="nav-item"><a class="nav-link active" href="#">Inicio</a></li>
        <li class="nav-item"><a class="nav-link" href="#servicios">Servicios</a></li>
        <li class="nav-item"><a class="nav-link" href="#contacto">Contacto</a></li>
      </ul>
    </div>
  </div>
</nav>

<!-- HERO -->
<section class="hero">
  <div class="container">
    <h1>Bienvenido a la Consultora de Matías Núñez</h1>
    <p>Soluciones digitales para tu negocio</p>
  </div>
</section>

<!-- SERVICIOS -->
<section id="servicios" class="py-5">
  <div class="container">
    <h2 class="text-center mb-4">Nuestros Servicios</h2>
    <div class="row g-4">
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/seed/1/400/250" class="card-img-top" alt="Servicio 1">
          <div class="card-body">
            <h5 class="card-title">Diseño Web</h5>
            <p class="card-text">Creamos sitios modernos, rápidos y adaptados a tus necesidades.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/seed/2/400/250" class="card-img-top" alt="Servicio 2">
          <div class="card-body">
            <h5 class="card-title">Consultoría Digital</h5>
            <p class="card-text">Te ayudamos a digitalizar tu empresa de forma efectiva.</p>
          </div>
        </div>
      </div>
      <div class="col-md-4">
        <div class="card">
          <img src="https://picsum.photos/seed/3/400/250" class="card-img-top" alt="Servicio 3">
          <div class="card-body">
            <h5 class="card-title">Soporte Técnico</h5>
            <p class="card-text">Asistencia profesional para tus sistemas y plataformas.</p>
          </div>
        </div>
      </div>
    </div>
  </div>
</section>

<!-- CARRUSEL -->
<div id="carouselExampleIndicators" class="carousel slide" data-bs-ride="carousel">
  <div class="carousel-indicators">
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="0" class="active"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="1"></button>
    <button type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide-to="2"></button>
  </div>
  <div class="carousel-inner">
    <div class="carousel-item active">
      <img src="https://picsum.photos/seed/car1/1200/400" class="d-block w-100" alt="Imagen 1">
    </div>
    <div class="carousel-item">
      <img src="https://picsum.photos/seed/car2/1200/400" class="d-block w-100" alt="Imagen 2">
    </div>
    <div class="carousel-item">
      <img src="https://picsum.photos/seed/car3/1200/400" class="d-block w-100" alt="Imagen 3">
    </div>
  </div>
  <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="prev">
    <span class="carousel-control-prev-icon"></span>
  </button>
  <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleIndicators" data-bs-slide="next">
    <span class="carousel-control-next-icon"></span>
  </button>
</div>

<!-- CONTACTO -->
<section id="contacto">
  <div class="container">
    <h2 class="text-center mb-4">Contáctanos</h2>
    <p class="text-center">Estás contactando con <strong>Matías Núñez</strong> — <a href="mailto:nunezmatiax@gmail.com">nunezmatiax@gmail.com</a></p>
    <form action="https://formsubmit.co/nunezmatiax@gmail.com" method="POST" class="row g-3">
      <input type="hidden" name="_captcha" value="false">
      <div class="col-md-6">
        <label for="nombre" class="form-label">Matías Núñez</label>
        <input type="text" class="form-control" id="nombre" name="nombre" value="Matías Núñez" readonly>
      </div>
      <div class="col-md-6">
        <label for="correo" class="form-label">nunezmatiax@gmail.com</label>
        <input type="email" class="form-control" id="correo" name="correo" value="nunezmatiax@gmail.com" readonly>
      </div>
      <div class="col-12">
        <label for="mensaje" class="form-label">¡Feliz por sus consultas! Deja tu mensaje aquí:</label>
        <textarea class="form-control" id="mensaje" name="mensaje" rows="4" required placeholder="Escribe tu consulta o mensaje con confianza..."></textarea>
      </div>
      <div class="col-12 text-center">
        <button type="submit" class="btn btn-success btn-lg">Enviar Consulta</button>
      </div>
    </form>
  </div>
</section>

<!-- SCRIPTS -->
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0/dist/js/bootstrap.bundle.min.js"></script>

</body>
</html>
