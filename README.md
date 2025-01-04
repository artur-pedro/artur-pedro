<!DOCTYPE html>
<html lang="pt-br">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Perfil do Pedro</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
    }
    h1, h2, h3 {
      color: #333;
      text-align: center;
    }
    a {
      text-decoration: none;
    }
    .section {
      margin: 30px auto;
      padding: 20px;
      max-width: 800px;
      background: #fff;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
    }
    .skills, .languages-tools {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 20px;
    }
    .projects, .hobbies {
      display: flex;
      flex-wrap: wrap;
      gap: 20px;
      justify-content: center;
    }
    .project-card, .hobby-card {
      background: #fefefe;
      border-radius: 8px;
      padding: 15px;
      text-align: center;
      box-shadow: 0 2px 6px rgba(0, 0, 0, 0.1);
      max-width: 200px;
    }
    footer {
      text-align: center;
      margin-top: 40px;
      padding: 10px;
      background: #333;
      color: white;
    }
    footer a {
      color: #0077B5;
    }
  </style>
</head>
<body>
  <!-- Header -->
  <h1>Olá! Me chamo Pedro 👋</h1>
  <h3>Sou estudante de Ciência da Computação</h3>

  <!-- Linkedin -->
  <div class="section">
    <h2>Converse comigo:</h2>
    <div style="text-align: center;">
      <a href="https://www.linkedin.com/in/artur-pedro/">
        <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
      </a>
    </div>
  </div>

  <!-- Skills -->
  <div class="section">
    <h2>👨‍💻 Skills</h2>
    <div style="display: flex; justify-content: center; gap: 80px; margin-top: 20px;">
      <img src="https://github-readme-stats.vercel.app/api?username=artur-pedro&show_icons=true&theme=dracula" alt="GitHub Stats">
      <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=artur-pedro" alt="Top Languages">
    </div>
  </div>

  <!-- Languages and Tools -->
  <div class="section">
    <h2>🔧 Languages and Tools</h2>
    <div class="languages-tools">
      <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
      <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
      <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
      <img src="https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white" alt="PHP">
      <img src="https://img.shields.io/badge/MySQL-00000F?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL">
      <img src="https://img.shields.io/badge/Python-14354C?style=for-the-badge&logo=python&logoColor=white" alt="Python">
      <img src="https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white" alt="C">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java">
      <img src="https://img.shields.io/badge/Fedora-294172?style=for-the-badge&logo=fedora&logoColor=white" alt="Fedora">
      <img src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white" alt="Figma">
    </div>
  </div>

  <!-- Projects -->
  <div class="section">
    <h2>📂 Projetos Recentes</h2>
    <div class="projects">
      <div class="project-card">
        <h3>Projeto 1</h3>
        <p>Descrição breve do projeto.</p>
        <a href="#">Ver mais</a>
      </div>
      <div class="project-card">
        <h3>Projeto 2</h3>
        <p>Descrição breve do projeto.</p>
        <a href="#">Ver mais</a>
      </div>
    </div>
  </div>

  <!-- Hobbies -->
  <div class="section">
    <h2>🎨 Hobbies</h2>
    <div class="hobbies">
      <div class="hobby-card">
        <h3>Leitura</h3>
        <p>Amo livros de ficção e ciência.</p>
      </div>
      <div class="hobby-card">
        <h3>Gaming</h3>
        <p>Jogos como Minecraft e LoL.</p>
      </div>
    </div>
  </div>

  <!-- Footer -->
  <footer>
    <p>Feito com ❤️ por Pedro | <a href="https://www.linkedin.com/in/artur-pedro/">LinkedIn</a></p>
  </footer>
</body>
</html>
