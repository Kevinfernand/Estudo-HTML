<!DOCTYPE html>
<html lang="pr-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="index.css">
  <script src="js/index.js"></script>
  <link rel="shortcut icon" href="2.png" type="image/x-icon" >
  <title>Estudo</title>
  <style>
        /* Reset Geral */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  font-family: Arial, sans-serif;
  line-height: 1.6;
  color: #333;
  background-color: #f4f4f4;
}

/* Cabeçalho */
.header {
  text-align: center;
  background-color: #2a2a2a;
  color: white;
  padding: 1.5rem;
}

.header h1 {
  font-size: 2.5rem;
}

.header p {
  font-size: 1.2rem;
}

/* Seção Hero */
.hero {
  text-align: center;
  padding: 2rem;
  background-color: #fff;
}

.hero img {
  max-width: 50%;
  height: auto;
  border-radius: 8px;
  margin-bottom: 1rem;
}

.hero h2 {
  font-size: 2rem;
  margin: 1rem 0;
}

.hero p {
  font-size: 1.2rem;
  margin-bottom: 1.5rem;
}

.hero button {
  padding: 0.75rem 1.5rem;
  font-size: 1rem;
  color: white;
  background-color: #007BFF;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.hero button:hover {
  background-color: #0056b3;
}

/* Seção Sobre */
.about-section {
  padding: 2rem;
  background-color: #f9f9f9;
  text-align: center;
}

.about-section h2 {
  font-size: 1.8rem;
  margin-bottom: 1rem;
}

.about-section ul {
  list-style-type: disc;
  list-style-position: outside;
  margin: 0 auto;
  padding-left: 2rem;
  text-align: left;
  display: inline-block;
}

/* Rodapé */
.footer {
  text-align: center;
  padding: 1rem;
  background-color: #2a2a2a;
  color: white;
  font-size: 0.9rem;
}
  </style>
</head>
<body>
  <header class="header">
    <h1>Aprendendo HTML</h1>
    <p>Estou aprendendo o básico do desenvolvimento web!</p>
  </header>

  <section class="hero">
    <img src="2.png" alt="HTML e Web Design" width="100" class="hero-image">
    <h2>Estudo HTML</h2>
    <p>Eu estou aprendo o basico como desenvolver um site.</p>
   <p>O HTML é composto por uma série de marcações, chamadas tags e atributos, que indicam ao navegador como exibir o conteúdo. Por exemplo, as tags podem ser usadas para: Colocar links em palavras ou imagens, Colocar palavras em itálico, Aumentar ou diminuir a fonte.</p> 
   <p>O HTML é composto por uma série de marcações, chamadas tags e atributos, que indicam ao navegador como exibir o conteúdo. Por exemplo, as tags podem ser usadas para: Colocar links em palavras ou imagens, Colocar palavras em itálico, Aumentar ou diminuir a fonte.</p> 
   <ul class="about-section">
  <li>O HTML é usado em diversas áreas, como:</li>
  <li>Desenvolvimento frontend, ou seja, na parte visual das aplicações web</li>
  <li>Desenvolvimento de aplicativos mobile</li>
  <li>Desenvolvimento de jogos</li>
  </ul>
  
<p>O HTML foi criado por Tim Berners-Lee, um físico britânico, e a primeira versão foi publicada em 1991. O World Wide Web Consortium (W3C) é responsável por manter e desenvolver as especificações do HTML.</p>
<p>O HTML foi criado por Tim Berners-Lee, um físico britânico, e a primeira versão foi publicada em 1991. O World Wide Web Consortium (W3C) é responsável por manter e desenvolver as especificações do HTML.</p>

    <button class="btn-scroll" onclick="scrollToSection()">Saiba Mais</button>
  </section>

  <section id="about" class="about-section">
    <h2>Por que aprender HTML?</h2>
    <p>Com o HTML, você pode criar:</p>
    <ul>
      <li>Sites simples e funcionais</li>
      <li>Estruturas para projetos avançados</li>
      <li>Plataformas responsivas</li>
    </ul>
    <h3>Como começar?</h3>
    <p>
      Para começar com HTML, você só precisa de um editor de texto (como o Notepad++) e um navegador.
      Com algumas linhas de código, já pode criar sua primeira página!
    </p>
  </section>

  <footer class="footer">
    <p>&copy; 2025 Aprenda HTML. Todos os direitos reservados.</p>
  </footer>
</body>
</html>



