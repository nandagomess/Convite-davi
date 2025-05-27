<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Convite do Davi - 3 Aninhos</title>
  <style>
    body {
      margin: 0;
      font-family: 'Arial', sans-serif;
      background: linear-gradient(to bottom, #1e1e2f, #4a4a8a);
      color: white;
      text-align: center;
      overflow-x: hidden;
    }
    h1 {
      font-size: 2.5rem;
      margin-top: 1.5rem;
    }
    h2 {
      font-size: 1.5rem;
      margin: 1rem 0;
    }
    .heroes {
      display: flex;
      justify-content: center;
      flex-wrap: wrap;
      gap: 20px;
      margin: 2rem 0;
      animation: fadeIn 2s ease-in;
    }
    .heroes img {
      width: 120px;
      transition: transform 0.3s;
    }
    .heroes img:hover {
      transform: scale(1.1);
    }
    .buttons {
      margin: 2rem 0;
    }
    .btn {
      background-color: #ffcc00;
      color: black;
      border: none;
      padding: 1rem 2rem;
      margin: 1rem;
      font-size: 1.1rem;
      border-radius: 8px;
      cursor: pointer;
      text-decoration: none;
      display: inline-block;
    }
    .footer {
      margin-top: 3rem;
      font-size: 0.9rem;
      color: #ccc;
    }
    @keyframes fadeIn {
      from { opacity: 0; transform: translateY(30px); }
      to { opacity: 1; transform: translateY(0); }
    }
  </style>
</head>
<body>
  <h1>ATENÇÃO, HERÓIS!</h1>
  <h2>O Super Davi está fazendo 3 aninhos!</h2>
  <p>Prepare sua capa e venha comemorar essa missão especial com a gente!</p>

  <div class="heroes">
    <img src="https://i.imgur.com/g6bYzpL.png" alt="Batman" />
    <img src="https://i.imgur.com/lBN9RJu.png" alt="Hulk" />
    <img src="https://i.imgur.com/0IVlNsV.png" alt="Homem-Aranha" />
    <img src="https://i.imgur.com/5AHtStS.png" alt="Thor" />
    <img src="https://i.imgur.com/EKqvO7N.png" alt="Capitão América" />
  </div>

  <div class="buttons">
    <a href="#" class="btn" id="btn-maps">📍 Ver local</a>
    <a href="#" class="btn" id="btn-whatsapp">✅ Confirmar presença</a>
  </div>

  <div class="footer">
    Em breve mais detalhes dessa aventura!<br/>
    Davi conta com a sua presença! 💛
  </div>

  <script>
    // Atualize os links quando tiver as informações reais
    document.getElementById('btn-maps').href = 'https://www.google.com/maps';
    document.getElementById('btn-whatsapp').href = 'https://wa.me/55SEUNUMERO';
  </script>
</body>
</html>
