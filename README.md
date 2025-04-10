# mini-voiture
<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Mini-Voiture Électrique</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      background-color: #f4f4f4;
      color: #333;
      text-align: center;
      padding: 20px;
    }

    h1 {
      color: #1a73e8;
    }

    .gallery {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
      margin-top: 30px;
    }

    .gallery img {
      width: 250px;
      height: auto;
      border-radius: 10px;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
    }

    .gallery img:hover {
      transform: scale(1.05);
    }

    .caption {
      font-size: 0.9em;
      color: #555;
      margin-top: 5px;
    }

    footer {
      margin-top: 40px;
      font-size: 0.9em;
      color: #777;
    }
  </style>
</head>
<body>

  <h1>🚗 Mini-Voiture Électrique Solaire</h1>
  <p>Présentation des composants utilisés pour la réalisation d'une voiture électrique autonome et connectée.</p>

  <div class="gallery">
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/3/38/Arduino_Uno_-_R3.jpg" alt="Arduino UNO">
      <div class="caption">Arduino UNO Rev3</div>
    </div>
    <div>
      <img src="https://cdn.sparkfun.com//assets/parts/1/1/0/3/14326-Arduino_Motor_Shield_R3-01.jpg" alt="Motor Shield">
      <div class="caption">Motor Shield</div>
    </div>
    <div>
      <img src="https://www.waveshare.com/img/devkit/b/solar-power-management-module-3.jpg" alt="Solar Charger">
      <div class="caption">Solar Charger Shield v2.2</div>
    </div>
    <div>
      <img src="https://cdn.shopifycdn.net/s/files/1/0045/0545/4364/products/HM-19-Bluetooth-5.0-Module_1200x1200.jpg" alt="Bluetooth HM-19">
      <div class="caption">Module Bluetooth HM-19</div>
    </div>
    <div>
      <img src="https://5.imimg.com/data5/SELLER/Default/2021/12/TD/NL/XN/49699819/eunicell-523450.jpg" alt="Batterie">
      <div class="caption">Batterie Li-ion 523450</div>
    </div>
    <div>
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/82/Breadboard.jpg" alt="Breadboard">
      <div class="caption">Breadboard</div>
    </div>
  </div>

  <footer>
    Projet Arduino – Mini-voiture connectée – 2024
  </footer>

</body>
</html>
