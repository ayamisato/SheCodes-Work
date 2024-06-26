<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Document</title>
    <style>
      h1 {
        text-align: center;
        margin: 0;
        font-size: 34px;
      }
      .body {
        font-family: Arial, Helvetica, sans-serif;
      }
      .current {
        text-align: center;
        font-size: 34px;
        font-weight: bold;
        color: #1a64d6;
      }
      .header-temp {
        text-align: center;
        font-size: 34px;
        margin: 10px;
      }
      .farenheit {
        font-weight: bold;
      }
      .weather {
        display: block;
        margin: 0 auto;
        font-size: 18px;
        background: transparent;
        border: none;
        padding: 30px 150px;
        border-radius: 10px;
        transition: all 200ms ease-in-out;
      }
      .weather:hover {
        background: #fffbef;
      }
      .day {
        font-weight: bold;
        font-size: 1.17em;
      }
      p {
        margin: 25px 0px 0px 0px;
        font-family: "Courier New", Courier, monospace;
        font-size: 20px;
      }
      .change {
        display: block;
        margin: 0 auto;
        font-size: 16px;
        background: #1a64d6;
        color: white;
        border: 1px solid #1a58d2;
        padding: 20px;
        border-radius: 30px;
        box-shadow: rgba(37, 39, 89, 0.08) 0px 8px 8px 0;
        transition: all 200ms ease-in-out;
      }
      .change:hover {
        background: #7f192f;
        cursor: pointer;
      }
      .footer {
        text-align: center;
        font-family: "Courier New", Courier, monospace;
        font-size: 18px;
        margin-top: 30px;
      }
    </style>
  </head>
  <body>
    <div class="body">
      <h1>🌤️</h1>
      <div class="current">Currently 21º in Tokyo</div>
      <div class="header-temp">13º / <span class="farenheit">23º</span></div>
      <button class="weather">
        <span class="day">🌧️ Tomorrow</span>
        <p class="temps">10º / <span class="farenheit">22º</span></p>
      </button>
      <button class="weather">
        <span class="day">🌥️ Saturday</span>
        <p class="temps">15º / <span class="farenheit">17º</span></p>
      </button>
      <button class="weather">
        <span class="day">☀️ Sunday</span>
        <p class="temps">25º / <span class="farenheit">28º</span></p>
      </button>
      <br />
      <button class="change">Change city</button>
    </div>
    <div class="footer">Coded by Ayami Sato</div>
  </body>
</html>
