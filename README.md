<style>
  /* Animação de digitação */
  @keyframes typing {
    from { width: 0; }
    to { width: 100%; }
  }

  @keyframes blink-caret {
    from, to { border-color: transparent; }
    50% { border-color: white; }
  }

  .typing-effect {
    font-family: 'Courier New', Courier, monospace;
    color: #4CAF50; /* Verde estilo terminal */
    overflow: hidden; /* Esconde o texto não digitado */
    border-right: .15em solid #fff; /* O cursor */
    white-space: nowrap; /* Mantém o texto em uma linha */
    margin: 0 auto;
    letter-spacing: .15em;
    font-size: 2em;
    font-weight: bold;
    display: inline-block;
    animation: 
      typing 3.5s steps(30, end),
      blink-caret .75s step-end infinite;
  }

  /* Centralização global */
  .profile-container {
    text-align: center;
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
  }

  /* Estilo para as seções de ferramentas */
  .tech-stack-section {
    margin-top: 30px;
    margin-bottom: 20px;
  }

  .tech-stack-title {
    font-size: 1.5em;
    margin-bottom: 10px;
    color: #fff;
    border-bottom: 2px solid #ED8B00; /* Linha laranja do Java */
    display: inline-block;
    padding-bottom: 5px;
  }

  .tech-badge-group {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 10px;
    margin-top: 10px;
  }

  /* Estilo para os cards de estatísticas */
  .stats-container {
    display: flex;
    justify-content: center;
    flex-wrap: wrap;
    gap: 15px;
    margin-top: 30px;
  }
</style>

<div class="profile-container">

  <br>
  <div class="typing-effect">
    Olá, eu sou Willian da Cunha Lima
  </div>
  <br>
  <p style="font-size: 1.2em; color: #aaa; margin-top: 10px;">
    Desenvolvedor Backend | Especialista em Java & Spring Boot
  </p>

  <div class="tech-stack-section">
    <div class="tech-stack-title">Ferramentas que eu utilizo:</div>
    
    <div class="tech-badge-group">
      <img src="https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java" />
      
      <img src="https://img.shields.io/badge/Spring_Boot-6DB33F?style=for-the-badge&logo=spring-boot&logoColor=white" alt="Spring Boot" />
      
      <img src="https://img.shields.io/badge/AWS-232F3E?style=for-the-badge&logo=amazon-aws&logoColor=white" alt="AWS" />
      
      <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker" />
      
      <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python" />
      
      <img src="https://img.shields.io/badge/MySQL-005C84?style=for-the-badge&logo=mysql&logoColor=white" alt="MySQL" />
      
      <img src="https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white" alt="PostgreSQL" />
      
      <img src="https://img.shields.io/badge/Postman-FF6C37?style=for-the-badge&logo=postman&logoColor=white" alt="Postman" />
    </div>
  </div>

  <hr style="border: 1px solid #333; margin: 30px 0;">

  <div align="left" style="max-width: 800px; margin: 0 auto;">
    <p>👋 Sou um desenvolvedor focado em construir soluções de backend robustas e escaláveis, utilizando o poder do ecossistema Java. Atualmente, atuo como **Jovem Aprendiz no Mercado Livre** e também desenvolvo projetos freelance como sistemas de gestão (como o JR Pesados). Sou estudante de Análise e Desenvolvimento de Sistemas no Mackenzie e apaixonado por arquitetura, performance e eficiência.</p>
  </div>

  <hr style="border: 1px solid #333; margin: 30px 0;">

  <div class="stats-container">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=williancunha95-spec&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true" alt="Willian's GitHub Stats" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=williancunha95-spec&layout=compact&theme=tokyonight" alt="Willian's Top Langs" />
  </div>

  <hr style="border: 1px solid #333; margin: 30px 0;">

  <div style="margin-top: 30px; margin-bottom: 20px;">
    <a href="https://www.linkedin.com/in/willian-da-cunha-lima-1a1ba1348/" target="_blank">
      <img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
  </div>

</div>
