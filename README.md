<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>La Casa del Pay</title>
  <style>
    body { font-family: Arial; margin: 0; padding: 0; background: #fff8f0; }
    header { background-color: #d2691e; color: white; padding: 20px; text-align: center; }
    nav a { margin: 0 15px; color: white; text-decoration: none; }
    .producto { border: 1px solid #ccc; margin: 20px; padding: 10px; border-radius: 10px; background: white; }
    .producto img { width: 100%; max-width: 300px; border-radius: 10px; }
    .productos { display: flex; flex-wrap: wrap; justify-content: center; }
    footer { background: #333; color: white; text-align: center; padding: 10px; }
  </style>
</head>
<body>

<header>
  <h1>La Casa del Pay</h1>
  <nav>
    <a href="#productos">Productos</a>
    <a href="#contacto">Contacto</a>
  </nav>
</header>

<section id="productos" class="productos">
  <div class="producto">
    <h2>Pay de Limón</h2>
    <img src="blob:https://web.whatsapp.com/34845311-a3d4-4d27-afda-7a4c7847a12c" alt="Pay de Limón">
    <p>Refrescante y delicioso. Ideal para días calurosos.</p>
    <strong>$120 MXN</strong>
  </div>

  <div class="producto">
    <h2>Pay de Queso</h2>
    <img src="blob:https://web.whatsapp.com/198556ec-6fdb-4a0f-9c22-cd84ea942461" alt="Pay de Queso">
    <p>Suave y cremoso, con base de galleta.</p>
    <strong>$140 MXN</strong>
  </div>

  <!-- Puedes agregar más productos así -->
</section>

<section id="contacto" style="text-align:center; padding: 20px;">
  <h2>Haz tu pedido</h2>
  <p>Contáctanos por WhatsApp:</p>
  <a href="https://wa.me/5215555555555" target="_blank" style="font-size:20px;">📱 Enviar mensaje</a>
</section>

<footer>
  <p>&copy; 2025 La Casa del Pay - Todos los derechos reservados</p>
</footer>

</body>
</html>
