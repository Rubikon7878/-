<!DOCTYPE html><html lang="uk">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Підтримай ЗСУ</title>
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&display=swap" rel="stylesheet">
  <style>
    * {
      box-sizing: border-box;
    }
    body {
      font-family: 'Roboto', sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #0057b7, #ffd700);
      color: #212529;
    }
    header {
      background-color: rgba(0, 0, 0, 0.7);
      color: #fff;
      padding: 2rem 1rem;
      text-align: center;
      position: relative;
      overflow: hidden;
    }
    header::before {
      content: "";
      position: absolute;
      top: 0; left: 0; right: 0; bottom: 0;
      background: url('https://upload.wikimedia.org/wikipedia/commons/5/5b/Flag_of_Ukraine.svg') center/cover no-repeat;
      opacity: 0.1;
      z-index: 0;
    }
    header h1, header p {
      position: relative;
      z-index: 1;
    }
    section {
      background-color: rgba(255, 255, 255, 0.95);
      padding: 2rem 1rem;
      max-width: 900px;
      margin: 2rem auto;
      border-radius: 12px;
      box-shadow: 0 4px 15px rgba(0, 0, 0, 0.1);
    }
    h2 {
      color: #003366;
      font-size: 1.5rem;
      text-align: center;
    }
    .donate-button {
      display: block;
      width: 100%;
      background-color: #28a745;
      color: #fff;
      padding: 1rem;
      font-size: 1.2rem;
      text-align: center;
      text-decoration: none;
      border-radius: 8px;
      transition: background-color 0.3s ease, transform 0.2s;
      margin: 1rem 0;
    }
    .donate-button:hover {
      background-color: #218838;
      transform: scale(1.03);
    }
    iframe {
      width: 100%;
      height: 500px;
      border: none;
      border-radius: 12px;
      margin-top: 1rem;
    }
    ul {
      list-style: none;
      padding-left: 0;
    }
    ul li::before {
      content: "\1F1FA\1F1E6 ";
      margin-right: 0.5rem;
    }
    .hero-img {
      width: 100%;
      border-radius: 12px;
      margin: 1rem 0;
    }
    footer {
      text-align: center;
      padding: 1rem;
      background-color: #003366;
      color: #fff;
      font-weight: bold;
      font-size: 0.9rem;
    }
    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8rem;
      }
      h2 {
        font-size: 1.3rem;
      }
      .donate-button {
        font-size: 1rem;
        padding: 0.75rem;
      }
      iframe {
        height: 400px;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Підтримай Збройні Сили України</h1>
    <p>Разом до перемоги! Слава Україні!</p>
  </header>  <section>
    <img class="hero-img" src="https://upload.wikimedia.org/wikipedia/commons/thumb/0/04/Ukrainian_soldiers_flag_2022.jpg/1280px-Ukrainian_soldiers_flag_2022.jpg" alt="Захисники України">
    <h2>Кожна гривня має значення</h2>
    <p style="text-align: center">Підтримай наших героїв. Зроби донат та допоможи забезпечити необхідним тих, хто боронить нашу землю.</p>
    <a class="donate-button" href="https://send.monobank.ua/jar/7hXTFizuzX" target="_blank">Задонатити</a>
    <iframe src="https://send.monobank.ua/jar/7hXTFizuzX"></iframe>
  </section>  <section>
    <h2>На що йдуть кошти:</h2>
    <ul>
      <li>Дрони та техніка</li>
      <li>Засоби зв'язку</li>
      <li>Бронежилети, каски</li>
      <li>Медичні аптечки</li>
      <li>Пальне та логістика</li>
    </ul>
  </section>  <footer>
    © 2025 Підтримка ЗСУ | Разом ми сила! | Героям слава!
  </footer>
</body>
</html>
