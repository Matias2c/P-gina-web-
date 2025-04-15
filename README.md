<!-- CONTACTO -->
<section id="contacto">
  <div class="container">
    <h2 class="text-center mb-4">Contáctanos</h2>
    <p class="text-center">Estás contactando con <strong>Matías Núñez</strong> — <a href="mailto:nunezmatiax@gmail.com">nunezmatiax@gmail.com</a></p>
    <form action="https://formsubmit.co/nunezmatiax@gmail.com" method="POST" class="row g-3">
      <input type="hidden" name="_captcha" value="false">

      <div class="col-md-6">
        <label for="nombre" class="form-label">Nombre del Asesor</label>
        <input type="text" class="form-control" id="nombre" name="nombre" value="Matías Núñez - Especialista en soluciones digitales" readonly>
      </div>

      <div class="col-md-6">
        <label for="correo" class="form-label">Correo de contacto</label>
        <input type="email" class="form-control" id="correo" name="correo" value="nunezmatiax@gmail.com - Respuesta rápida garantizada" readonly>
      </div>

      <div class="col-12">
        <label for="mensaje" class="form-label">¡Feliz por tus consultas!</label>
        <textarea class="form-control" id="mensaje" name="mensaje" rows="4" required placeholder="Cuéntame sobre tu proyecto, duda o idea. Estoy aquí para ayudarte a crecer digitalmente.">Hola Matías, me interesa saber más sobre tus servicios digitales. Me gustaría agendar una consulta personalizada. ¡Gracias!</textarea>
      </div>

      <div class="col-12 text-center">
        <button type="submit" class="btn btn-success btn-lg d-inline-flex align-items-center gap-2 transition">
          <i class="bi bi-send-fill"></i> Enviar Consulta Personalizada
        </button>
      </div>
    </form>
  </div>
</section>

<!-- Bootstrap Icons y Estilos -->
<link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/bootstrap-icons@1.10.5/font/bootstrap-icons.css">
<style>
  .btn.transition {
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  .btn.transition:hover {
    transform: scale(1.05);
    box-shadow: 0 0 12px rgba(40, 167, 69, 0.5);
  }
</style>
