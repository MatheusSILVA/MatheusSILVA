
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <style>
      * {
  margin: 0;
  padding: 0;
}

body {
  background-color: #12172b;
  color: white;
  font-family: "Poppins", sans-serif;
}

h1 {
  text-align: center;
  margin-top: 40px;
  font-size: 80px;
}

.skills-area {
  display: flex;
  flex-direction: column;
  padding: 0 20%;
}

.skill {
  position: relative;
  margin-bottom: 40px;
}

.skill-title {
  font-size: 40px;
  margin-bottom: 10px;
}

.skill-bar {
  width: 100%;
  background: rgba(255, 255, 255, 0.6);
  height: 40px;
  z-index: -1;
  border-radius: 100px;
  position: absolute;
}

.skill-fill {
  background: blue;
  height: 40px;
  border-radius: 100px;
  display: flex;
  justify-content: flex-end;
  align-items: center;
  padding-right: 30px;
  overflow: hidden;
}

.skill-percent {
  font-size: 30px;
}

.html {
  animation: html 2s;
  width: 50%;
}

.css {
  animation: css 2s;
  width: 80%;
}

.js {
  animation: js 2s;
  width: 70%;
}

@keyframes html {
  from {
    width: 0;
  }
  to {
    width: 50%;
  }
}

@keyframes css {
  from {
    width: 0;
  }
  to {
    width: 80%;
  }
}

@keyframes js {
  from {
    width: 0;
  }
  to {
    width: 70%;
  }
}

@media only screen and (max-width: 750px) {
  .skills-area {
    padding: 0 5%;
  }
}

    </style>
  </head>

  <body>
    <h1>My Skills</h1>
    <div class="skills-area">
      <div class="skill">
        <div class="skill-title">HTML</div>
        <div class="skill-bar"></div>
        <div class="html skill-fill">
          <span class="skill-percent">50%</span>
        </div>
      </div>
      <div class="skill">
        <div class="skill-title">CSS</div>
        <div class="skill-bar"></div>
        <div class="css skill-fill">
          <span class="skill-percent">80%</span>
        </div>
      </div>
      <div class="skill">
        <div class="skill-title">JavaScript</div>
        <div class="skill-bar"></div>
        <div class="js skill-fill">
          <span class="skill-percent">70%</span>
        </div>
      </div>
    </div>
  </body>
</html>

- <h4>👋 Olá, eu me chamo @MatheusSILVA</h4>
- <h4>🌱 No momento estou aprendendo JS, CSS e IONIC</h4>
- <h4>👀 Estou interessado em adquirir novos conhecimentos!!</h4>
- <h4>💞️ Estou procurando colaborar, compartilahndo meu conhecimento!!</h4>
- <h4>📚 Estou cursando oúltimo ano em Análise e Desenvolvimento de Sistemas!!</h4>

