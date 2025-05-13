<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Happiest Birthday Saima 🎉</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: linear-gradient(to bottom right, #ffeaf4, #e5f0ff);
      display: flex;
      align-items: center;
      justify-content: center;
      height: 100vh;
      overflow: hidden;
    }

    .card {
      background: white;
      padding: 30px 25px;
      border-radius: 20px;
      box-shadow: 0 8px 30px rgba(0,0,0,0.1);
      text-align: center;
      max-width: 90%;
      animation: fadeIn 2s ease-in;
    }

    h1 {
      font-size: 2rem;
      color: #ff69b4;
      margin-bottom: 10px;
    }

    p {
      font-size: 1.1rem;
      color: #444;
    }

    .candles {
      position: absolute;
      bottom: 10px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 20px;
    }

    .candle {
      width: 25px;
      height: 60px;
      background-color: #f7b7a3;
      border-radius: 10px;
      position: relative;
    }

    .candle::before {
      content: "";
      position: absolute;
      top: -10px;
      left: 50%;
      transform: translateX(-50%);
      width: 8px;
      height: 20px;
      background-color: #f7b700;
      border-radius: 4px;
      animation: flicker 1.5s infinite alternate;
    }

    .flowers {
      position: absolute;
      bottom: 80px;
      left: 50%;
      transform: translateX(-50%);
      display: flex;
      gap: 30px;
    }

    .flower {
      width: 40px;
      height: 40px;
      background-color: #ff69b4;
      border-radius: 50%;
      box-shadow: 0 0 15px rgba(0,0,0,0.1);
    }

    .flower::after {
      content: "";
      position: absolute;
      top: 50%;
      left: 50%;
      width: 10px;
      height: 10px;
      background-color: #fff;
      border-radius: 50%;
      transform: translate(-50%, -50%);
    }

    @keyframes flicker {
      0% { transform: translateX(-50%) rotate(0deg); opacity: 0.8; }
      100% { transform: translateX(-50%) rotate(15deg); opacity: 1; }
    }

    @keyframes fadeIn {
      0% { opacity: 0; transform: scale(0.95); }
      100% { opacity: 1; transform: scale(1); }
    }
  </style>
</head>
<body>
  <div class="card">
    <h1>Happiest Birthday, Saima 🎂💖</h1>
    <p>
      On this very special day, I want to remind you how amazing and beautiful you are!  
      May your year be filled with endless happiness, love, and magical moments.  
      Wishing you all the joy in the world today and always 🌸🎉
    </p>
  </div>

  <!-- Candles -->
  <div class="candles">
    <div class="candle"></div>
    <div class="candle"></div>
    <div class="candle"></div>
  </div>

  <!-- Flowers -->
  <div class="flowers">
    <div class="flower"></div>
    <div class="flower"></div>
    <div class="flower"></div>
  </div>
</body>
</html>
