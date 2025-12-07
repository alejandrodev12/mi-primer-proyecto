<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mi primera página</title>
  <style>
    /* Estilos generales */
    body {
      color: #1a1a1a;
      background-color: #f5f5f5;
      font-family: Georgia, sans-serif;
      margin: 0;
      padding: 0;
    }

    header, footer {
      background-color: #4b0082;
      color: white;
      text-align: center;
      padding: 15px 0;
    }

    h1, h2 {
      margin: 10px 0;
    }

    p {
      color: #006400;
      line-height: 1.5;
      margin: 5px 0 15px 0;
    }

    .section {
      background-color: #eee;
      padding: 15px;
      margin: 15px auto;
      border-radius: 8px;
      max-width: 600px;
    }

    ul {
      padding-left: 20px;
    }

    a {
      color: darkred;
      text-decoration: none;
      font-weight: bold;
    }

    a:hover {
      color: orange;
    }

    .btn {
      display: inline-block;
      background-color: darkred;
      color: white;
      padding: 8px 12px;
      border-radius: 5px;
      margin: 5px 0;
      text-decoration: none;
      transition: background-color 0.3s;
    }

    .btn:hover {
      background-color: orange;
      color: black;
    }

    main {
      padding: 20px;
      text-align: center;
    }
  </style>
</head>
<body>

<header>
  <h1>Hola, mundo</h1>
</header>

<main>
  <p>Mi primer proyecto</p>
  <p>Sea serio ciervo</p>

  <div class="section">
    <h2>Mis frutas favoritas:</h2>
    <ul>
      <li>Manzana</li>
      <li>Plátano</li>
      <li>Naranja</li>
    </ul>
  </div>

  <div class="section">
    <h2>Enlaces útiles:</h2>
    <a class="btn" href="https://mx.pinterest.com/pin/385691155608455582/" target="_blank">Ir a Pinterest</a><br>
    <a class="btn" href="https://www.instagram.com/p/CvlMLjdL4yM/" target="_blank">Ir a Instagram</a>
  </div>
</main>

<footer>
  <p>Mi primera página web &copy; 2025</p>
</footer>

</body>
</html>
