<!DOCTYPE html><html lang="es">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>JC Deco Holistic</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #f5f5f5;
      color: #333;
    }
    header {
      background-color: #333;
      color: white;
      padding: 1rem;
      text-align: center;
    }
    nav {
      background-color: #444;
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
    }
    nav a {
      color: white;
      padding: 1rem;
      text-decoration: none;
      text-transform: uppercase;
    }
    nav a:hover {
      background-color: #666;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .catalogo {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 1rem;
    }
    .producto {
      background-color: white;
      padding: 1rem;
      border-radius: 8px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
    }
    .producto img {
      width: 100%;
      height: auto;
      border-radius: 8px;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 1rem;
    }
    .whatsapp {
      display: inline-block;
      margin-top: 1rem;
      background-color: #25D366;
      color: white;
      padding: 1rem;
      border-radius: 50px;
      text-decoration: none;
      font-weight: bold;
    }
    @media (max-width: 600px) {
      nav a {
        flex: 1 0 100%;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>JC Deco Holistic</h1>
    <p>Decoración, accesorios y aromas con alma</p>
  </header>
  <nav>
    <a href="#inicio">Inicio</a>
    <a href="#sobre">Sobre Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>  <section id="inicio">
    <h2>Catálogo de Productos</h2>
    <div class="catalogo">
      <div class="producto">
        <img src="https://via.placeholder.com/300x200" alt="Producto 1">
        <h3>Producto 1</h3>
        <p>Descripción breve del producto.</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/300x200" alt="Producto 2">
        <h3>Producto 2</h3>
        <p>Descripción breve del producto.</p>
      </div>
      <div class="producto">
        <img src="https://via.placeholder.com/300x200" alt="Producto 3">
        <h3>Producto 3</h3>
        <p>Descripción breve del producto.</p>
      </div>
      <!-- Puedes duplicar más bloques "producto" para agregar más items -->
    </div>
  </section>  <section id="sobre">
    <h2>Sobre Nosotros</h2>
    <p>En JC Deco Holistic creamos piezas únicas de decoración, accesorios y productos aromáticos hechos a mano. Nos apasiona llenar los espacios de energía positiva y estilo, combinando estética y bienestar.</p>
  </section>  <section id="contacto">
    <h2>Contacto</h2>
    <p>¿Quieres hacer un pedido o tienes alguna consulta? Escríbenos directamente:</p>
    <a class="whatsapp" href="https://wa.me/1234567890" target="_blank">Chatea por WhatsApp</a>
  </section>  <footer>
    <p>&copy; 2025 JC Deco Holistic. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
