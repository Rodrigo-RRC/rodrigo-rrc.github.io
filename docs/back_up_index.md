
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Portfólio Rodrigo Ribeiro Carvalho</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      padding: 2rem;
      text-align: center;
    }

    h1 {
      font-size: 2.5rem;
      color: #2c3e50;
    }

    .card {
      background-color: white;
      padding: 2rem;
      margin: 1rem;
      border-radius: 10px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
      transition: transform 0.3s ease;
      width: 280px;
    }

    .card:hover {
      transform: scale(1.05);
    }

    .card a {
      text-decoration: none;
      color: #2c3e50;
      font-size: 1.2rem;
      font-weight: bold;
    }

    .cards-container {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 2rem;
      margin-top: 2rem;
    }

    @media (max-width: 600px) {
      .cards-container {
        flex-direction: column;
        align-items: center;
      }
    }
  </style>
</head>
<body>
  <h1>🌐 Portfólio de Projetos</h1>
  <div class="cards-container">
    <div class="card">
      <a href="https://rodrigo-rrc.github.io/Projetos_Java/">☕ Projetos Java</a>
    </div>
    <div class="card">
      <a href="https://rodrigo-rrc.github.io/Projetos_BI/">📊 Projetos BI</a>
    </div>
    <div class="card">
      <a href="https://rodrigo-rrc.github.io/Projetos_IA/">🧠 Projetos IA</a>
    </div>
  </div>
</body>
</html>
