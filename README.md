<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Senda Natural - Energía que te acompaña</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1.5rem;
      text-align: center;
    }
    nav {
      background-color: #388E3C;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: white;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    .productos {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(250px, 1fr));
      gap: 2rem;
    }
    .producto {
      background: white;
      padding: 1rem;
      border-radius: 10px;
      box-shadow: 0 2px 5px rgba(0,0,0,0.1);
    }
    .producto h3 {
      margin-top: 0;
    }
    footer {
      background-color: #2E7D32;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Senda Natural</h1>
    <p>Energía que te acompaña</p>
  </header>
  
  <nav>
    <a href="#productos">Productos</a>
    <a href="#nosotros">Nosotros</a>
    <a href="#contacto">Contacto</a>
  </nav>

  <section id="productos">
    <h2>Nuestros Sabores</h2>
    <div class="productos">
      <div class="producto">
        <h3>Avena Dorada</h3>
        <p>Granola crujiente con miel pura. El clásico saludable.</p>
      </div>
      <div class="producto">
        <h3>Cacahuate Cremoso</h3>
        <p>Barras suaves con auténtica mantequilla de cacahuate.</p>
      </div>
      <div class="producto">
        <h3>Nuez Intensa</h3>
        <p>Chocolate oscuro y nueces para un snack más gourmet.</p>
      </div>
      <div class="producto">
        <h3>Dulce Balance</h3>
        <p>Cacahuates tostados y miel con un toque de sal.</p>
      </div>
      <div class="producto">
        <h3>Mix Vital</h3>
        <p>Arándanos, pasas, nueces y semillas para recargar tu día.</p>
      </div>
      <div class="producto">
        <h3>Manzana Especiada</h3>
        <p>Sabor casero con manzana y canela real.</p>
      </div>
    </div>
  </section>

  <section id="nosotros">
    <h2>Sobre Nosotros</h2>
    <p>Somos una empresa mexicana comprometida con ofrecer opciones de snacks saludables, prácticos y sabrosos. Creemos que comer bien debe ser fácil y delicioso.</p>
    <h3>Nuestra Historia</h3>
    <p>Senda Natural nació en 2023 cuando un grupo de amigos apasionados por la vida activa y la alimentación consciente decidió crear una alternativa real a los snacks ultraprocesados. Empezamos en una cocina casera, experimentando con recetas de barras que combinaran sabor, nutrición y practicidad. Poco a poco, nuestros productos ganaron popularidad en mercados locales, gimnasios y tiendas orgánicas. Hoy, seguimos fieles a nuestro propósito: ofrecer productos honestos, naturales y llenos de energía para acompañarte en tu día a día.</p>
  </section>

  <section id="contacto">
    <h2>Contacto</h2>
    <p>¿Tienes preguntas o quieres vender nuestros productos? Escríbenos a: <a href="mailto:info@sendanatural.com">info@sendanatural.com</a></p>
  </section>

  <footer>
    <p>&copy; 2025 Senda Natural. Todos los derechos reservados.</p>
  </footer>
</body>
</html>
