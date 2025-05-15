<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Meu Site Básico</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      text-align: center;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    header {
      background-color: #4CAF50;
      color: white;
      padding: 1rem;
    }
    main {
      padding: 2rem;
    }
    button {
      padding: 1rem 2rem;
      font-size: 1rem;
      background-color: #4CAF50;
      color: white;
      border: none;
      cursor: pointer;
      border-radius: 8px;
    }
    button:hover {
      background-color: #45a049;
    }
  </style>
</head>
<body>
  <header>
    <h1>Bem-vindo ao Meu Site</h1>
  </header>
  <main>
    <p>Este é um exemplo de site básico feito com HTML, CSS e JavaScript.</p>
    <button onclick="mudarCor()">Mudar Cor de Fundo</button>
  </main>

  <script>
    function mudarCor() {
      const cores = ['#f4f4f4', '#dcdcdc', '#fff0f5', '#e0ffff', '#fafad2'];
      document.body.style.backgroundColor = cores[Math.floor(Math.random() * cores.length)];
    }
  </script>
</body>
</html>
