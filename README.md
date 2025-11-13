<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Florería Cuatro Pétalos</title>
  <style>
    body {
      font-family: 'Georgia', serif;
      background-color: #fff8f8;
      color: #333;
      text-align: center;
      margin: 0;
      padding: 0;
    }

    header {
      background-color: #f4b6c2;
      padding: 20px;
      color: white;
      font-size: 2em;
      font-weight: bold;
      letter-spacing: 2px;
    }

    .galeria {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 30px;
      padding: 40px 20px;
    }

    .flor {
      background-color: #fff;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
      width: 250px;
      padding: 15px;
      transition: transform 0.2s;
    }

    .flor:hover {
      transform: scale(1.05);
    }

    img {
      width: 100%;
      height: 230px;
      object-fit: cover;
      border-radius: 10px;
    }

    .precio {
      font-size: 1.2em;
      color: #d63384;
      margin-top: 10px;
    }

    footer {
      background-color: #f4b6c2;
      color: white;
      padding: 15px;
      font-size: 1em;
    }

    .contacto {
      margin-top: 20px;
      font-size: 1.1em;
    }

    a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }
  </style>
</head>
<body>

  <header>
    🌸 Florería Cuatro Pétalos 🌸
  </header>

  <section class="galeria">
    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2016/03/27/07/08/tulip-1283603_1280.jpg" alt="Tulipán">
      <h3>Tulipán</h3>
      <p class="precio">$8.200</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2015/04/19/08/32/rose-729509_1280.jpg" alt="Rosa">
      <h3>Rosa</h3>
      <p class="precio">$2.000</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2016/03/05/19/02/sunflower-1234440_1280.jpg" alt="Girasol">
      <h3>Girasol</h3>
      <p class="precio">$5.000</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2018/03/15/09/31/carnation-3227093_1280.jpg" alt="Clavel">
      <h3>Clavel</h3>
      <p class="precio">$1.100</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2018/04/03/18/21/gerbera-3295907_1280.jpg" alt="Gerbera">
      <h3>Gerbera</h3>
      <p class="precio">$4.000</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2016/01/19/15/05/roses-1149949_1280.jpg" alt="Ramo de 40 Rosas">
      <h3>Ramo de 40 Rosas</h3>
      <p class="precio">$150.000</p>
    </div>

    <div class="flor">
      <img src="https://cdn.pixabay.com/photo/2017/04/05/01/17/gerbera-2207929_1280.jpg" alt="Ramo de 12 Gerberas Rojas">
      <h3>Ramo de 12 Gerberas Rojas</h3>
      <p class="precio">$135.000</p>
    </div>
  </section>

  <footer>
    <div>💐 Gracias por visitar nuestra florería 💐</div>
    <div class="contacto">
      📧 <a href="mailto:FloreríaCuatroPetalos@gmail.com">FloreríaCuatroPetalos@gmail.com</a><br>
      📞 +54 9 11 3456-7890
    </div>
  </footer>
