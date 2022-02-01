<template>
  <div class="home">
  <div class="P-1">
  <div class="content">
    <h2>David</h2>
    <h2>David</h2>
    <h3 class="post">Développeur & Integrateur Web</h3>
  </div>
    <div class="scroll-spc">
      <div id="triangle"></div>
    </div>
  </div>
  <div class="about" id="profile">
    <div class="left">
        <img alt="profile picture" src="../assets/img/profilePicture.jpeg" class="profilePicutre">
      <h1 class="name">Ruscuta David</h1>
      <h5>Étudiant Développement Web</h5>
      <img src="" alt="">
    </div>
    <div class="right">
      <h1>Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolore accusamus, perspiciatis suscipit commodi cupiditate iure quas nobis velit cum expedita sed possimus qui, consequatur aspernatur dicta dolor mollitia soluta. Ut.</h1>
    </div>
  </div>
        <h1 class="A-B-C">
        <span style="margin-left: 670px;">always be</span>
          <div class="message">
            <div class="word1">training</div>
            <div class="word2">coding</div>
            <div class="word3">creating</div>
          </div>
      </h1>
  <div class="competences">
    <h1 class="comp-txt">Maîtrise des differents languages</h1>
      <div class="langages">
        <div id="btn-html" class="comp">
          <h4 class="html">HTML 5</h4>
          <hr class="html-hr">
          <img src="../assets/img/html.png" alt="html logo" class="logo">
            <div class="comp-cont">
              <p class="p-html">Lorem ipsum dolor sit amet consectetur, adipisicing elit. Obcaecati et exercitationem aperiam, repellat similique enim quasi fugit laboriosam laborum architecto, rem illum veniam. Debitis officiis harum doloribus iusto soluta aspernatur.</p>
            </div>
        </div>
        <div id="btn-css" class="comp">
          <h4>CSS 3</h4>
          <hr class="css-hr">
          <img src="../assets/img/css.png" alt="css logo" class="logo">
            <div class="comp-cont">
              <p class="p-css">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Obcaecati unde nemo perferendis debitis sequi explicabo porro aliquam quis officiis impedit in temporibus, distinctio id provident repudiandae sed veniam placeat. Vero.</p>
            </div>
        </div>
        <div id="btn-js" class="comp">
          <h4>JAVASCRIPT</h4>
          <hr class="js-hr">
          <img src="../assets/img/js.png" alt="js logo" class="logo">
            <div class="comp-cont">
              <p class="p-js">Lorem ipsum dolor sit amet, consectetur adipisicing elit. Dolorem sint, quas possimus ipsa non cupiditate eum maiores dicta ex sequi error, necessitatibus repellat praesentium! Eius iure quam accusamus quaerat placeat.</p>
            </div>
        </div>
        <div id="btn-php" class="comp">
          <h4>PHP</h4>
          <hr class="php-hr">
          <img src="../assets/img/php.png" alt="php logo" class="logo">
            <div class="comp-cont">
              <p class="p-php">Lorem ipsum dolor sit, amet consectetur adipisicing elit. Expedita quibusdam maxime quis quisquam quaerat, dolore repellendus et? Dolores, repellendus minima. Earum rerum, eius excepturi reprehenderit perspiciatis quod molestias nihil voluptate?</p>
            </div>
        </div>
        <div id="btn-sql" class="comp">
          <h4>SQL</h4>
          <hr class="sql-hr">
          <img src="../assets/img/sql.png" alt="sql logo" class="logo">
            <div class="comp-cont">
              <p class="p-sql">Lorem ipsum dolor sit amet consectetur adipisicing elit. Expedita alias odio consectetur enim amet, ratione quod consequatur, autem non voluptates repudiandae provident officia dolor ab quisquam blanditiis placeat! Iure, dolorum.</p>
            </div>
        </div>
      </div>
  </div>
  <div class="trans"></div>
  <div class="formation">
    <div style="display: flex; justify-content: center;">
      <div style="display: flex;flex-direction: column; margin-right: 130px; margin-top: 37px;">
        <h1 style="color: white; ">Année Préparatoire 2021</h1>
        <h2 style="font-size: 15px;">Chargé de développement et de mise en oeuvre de projets SI</h2>
      </div>
      <img src="../assets/img/etna.png" alt="etnaPicture" class="etnaPicture">
    </div>
    <div class="project-list">
      <div class="project-card">
        <div>
        <h1 class="project-title">The Hyrule Castle</h1>
        <h5>09/21</h5>
        </div>
        <p>Jeu de type RPG basé sur l'univers "Zelda" avec un gameplay permettant de vaincre des "Boss" en contrôlant le jeu en interagissant avec les touches du clavier</p>
      </div>
      <div class="project-card">
        <div>
          <h1 class="project-title">Dungeon Keeper Game</h1>
          <h5>11/21</h5>
        </div>
        <p>"Clicker Game" basé sur l'univers "Dungeon Keeper Game". Incrémentation, Auto-Incrémentation et achats de bonus permettant l'évolution du jeu</p>
      </div>
      <div class="project-card">
        <div>
          <h1 class="project-title">Liberty Commerce</h1>
          <h5>10/21</h5>
        </div>
        <p>Site d'e-commerce pour vente de pianos avec création et gestion de comptes utilisateurs et des produits pour l'administrateur</p>
      </div>
      <div class="project-card">
        <div>
          <h1 class="project-title">Extension Mentor Goal</h1>
          <h5>12/21</h5>
        </div>
        <p>Outil visant à aider, faciliter et suivre les candidatures des differents clients</p>
      </div>
    </div>
  </div>
  </div>
  
</template>

<script>
</script>

<style>

.content {
  animation: fadeIn 4s;
}

@keyframes fadeIn {
  0% {
    opacity: 0%;
  }
  100% {
    opacity: 100%
  }
}

/*############################# Welcome */

.content {
  position: relative;
  display: flex;
  background: #000;
  min-height: 100vh;
  align-items: center;
  justify-content: center;
  box-shadow: 0px 0px 10px 2px black;
}

.content h2 {
  color: #fff;
  font-size: 8em;
  position: absolute;
  transform: translate(-50%, -50%);
}

.content h2:nth-child(1) {
  color: transparent;
  -webkit-text-stroke: 2px #03a9f4;
}

.content h2:nth-child(2) {
  color: #03a9f4;
  animation: animate 4s ease-in-out infinite;
}

.post {
  position: relative;
  text-transform: uppercase;
  letter-spacing: 2px;
  background: linear-gradient(90deg, #03a9f4, #fff, #000);
  background-size: 80%;
  animation: anim 5s infinite;
  -webkit-background-clip: text;
   -webkit-text-fill-color: rgba(255, 255, 255, 0);
}
      @keyframes anim {
        0% {
          background-position: -400%;
        }
        50% {
          background-position: 100%;
        }
        100% {
          background-position: 400%;
        }
      }

@keyframes animate {
  0%,
  100% {
    clip-path: polygon(
      0% 45%,
      16% 44%,
      33% 50%,
      54% 60%,
      70% 61%,
      84% 59%,
      100% 52%,
      100% 100%,
      0% 100%
    );
  }

  50% {
    clip-path: polygon(
      0% 60%,
      15% 65%,
      34% 66%,
      51% 62%,
      67% 50%,
      84% 45%,
      100% 46%,
      100% 100%,
      0% 100%
    );
  }
}

/*############################# Welcome message  */

h3 {
  font-size: 30px;
  position: absolute;
  animation: moveInH3 2s;
}

/*############################# Triangle  */

#triangle {
    margin-top: 720px;
    width: 0;
    height: 0;
    border-left: 18px solid transparent;
    border-right: 18px solid transparent;
    border-bottom: 30px solid rgba(255, 255, 255, 0.605);
    transform: rotate(180deg);
    position: absolute;
    animation: float 2s linear infinite;

}
    #triangle:hover {
    border-left: 18px solid transparent;
    border-right: 18px solid transparent;
    border-bottom: 30px solid #03a8f49c;
    }

  #triangle:target html {
    transform: translateX(800px);
  }

  .scroll-spc {
    animation: display 4s;
    margin-left: 700px;
  }

@keyframes display {
  0% {
    opacity: 0%;
  }
  90% {
    opacity: 1%;
  }
  100% {
    opacity: 100%;
  }
}

@keyframes float {
  0% {
    top: 0px;
  }
  50% {
    top: 10px;
  }
  100% {
    top: 0px;
  }
}

  @keyframes move-line {
    0%   {left:0px; top:0px; width: 20px;}
    25%  {left:745px; top:0px; width: 100px;}
    50%  {left:1480px; top:0px; width:20px}
    75%  {left:745px; top:0px; width:100px}
    100% {left:0; top:0px; width: 20px;}
  }

/*############################# About */

  .about {
    margin-top: 100px;
    display: flex;
    flex-direction: row;
    justify-content: baseline;
    height: 580px;
    width: 100%;
    padding: 50px;
  }

  .name {
    margin-top: 20px;
    font-size: 40px;
  }
  
  .profilePicutre {
    height: 400px;
    width: auto;
  }

  .nuage {
    bottom: 100px;
    width: 500px;
    height: auto;
  }

  .right {
    margin-top: 100px;
    padding: 50px;
  }

/*############################# Transition */

.trans {
  background: linear-gradient(to bottom, yellow,#03a9f4);
  height: 200px;
}

/*############################# Formation */

.formation {
  background: #03a9f4;
  height: 789px;
  padding: 50px;
}

.etnaPicture {
  width: 300px;
  height: auto;

  margin-bottom: 50px;
}

.project-list {
  display: flex;
  flex-wrap: wrap;
  justify-content: space-around;
  gap: 30px;
}

.project-card {
  display: flex;
  flex-direction: column;
  background-color: #00acfc;
  width: 400px;
  height: 200px;
  padding: 20px;
  justify-content: space-around;

  border-radius: 20px;

  box-shadow: 0px 5px 5px 2px #0d94d3;
}

.project-card:hover {
  width: 430px;
  transition-duration: 0.3s;
  background-color: white;
  box-shadow: 0px 5px 5px 2px rgba(255, 255, 255, 0.371);
  color: black;
}

/*############################# Competences */

.competences {
    height: 400px;
    margin: 0 auto;
    padding: 2%;
    /*background: rgb(144, 228, 70);*/
    background: yellow;
  }

    h4 {
    text-align: center;
    font-size: 25px;
    display: none;
  }

    .langages {
      margin-top: 50px;
    display: flex;
    flex-wrap: wrap;
    justify-content: space-between;
  }

  .comp {
    width: 250px;
    height: 150px;
  
    display: flex;
    padding: 10px;
    flex-wrap: wrap;
    flex-direction: column;
    align-items: center;
    overflow: hidden;

    box-shadow: 0px 5px 5px 2px rgba(0, 0, 0, 0.371);

    border-radius: 10px;
    cursor: pointer;
  }
  
  .comp:hover {
    transition-duration: 0.5s;
    background: white;
    box-shadow: 0px 0px 10px 2px #7c81839c;
    
    width: 300px;
    height: 300px;
  }
  
  .comp:hover .logo{
    display: none;
  }
  
  .comp:hover h4{
    animation-duration: 0.5s;
    display: block;

  }

  .comp-cont {
    display: flex;
    align-items: center;
    flex-direction: row;
    justify-content: space-between;
    
  }

  hr {
    display: none;
    width: 240px;
  }

  progress {
    margin-top: 50px;
    width: 240px;
  }
  
  .p-html {display: none; margin-top: 20px;}.html-lvl {display: none;}#btn-html:hover .p-html{display: block;}#btn-html:hover .html-lvl{display: block;}#btn-html:hover .html-hr{display: block;}
  .p-css {display: none; margin-top: 20px;}.css-lvl {display: none;}#btn-css:hover .p-css {display: block;}#btn-css:hover .css-lvl{display: block;}#btn-css:hover .css-hr{display: block;}
  .p-js {display: none; margin-top: 20px;}.js-lvl {display: none;}#btn-js:hover .p-js {display: block;}#btn-js:hover .js-lvl{display: block;}#btn-js:hover .js-hr{display: block;}
  .p-php {display: none; margin-top: 20px;}.php-lvl {display: none;}#btn-php:hover .p-php {display: block;}#btn-php:hover .php-lvl{display: block;}#btn-php:hover .php-hr{display: block;}
  .p-sql {display: none; margin-top: 20px;}.sql-lvl {display: none;}#btn-sql:hover .p-sql {display: block;}#btn-sql:hover .sql-lvl{display: block;}#btn-sql:hover .sql-hr{display: block;}

   .logo {
    margin-top: 20px;
    height: 100px;
    width: 100px;
  }

/*############################# Maitrise Text  */

  .comp-txt {
    color: #333;
    font-family: tahoma;
    font-size: 50px;
    font-weight: 900;
    line-height: 1.5;
    text-transform: uppercase;
    display: flex;
    padding-left: 0px;
    max-width: 40ch;
    text-align: center;
    transform: scale(0.94);
    animation: scale 3s forwards cubic-bezier(0.5, 1, 0.89, 1);
    margin-top: 10px;
  }
/*#############################@ Always be Code */
.A-B-C {
  color: #333;
  font-family: tahoma;
  font-size: 3rem;
  font-weight: 100;
  line-height: 1.5;
  text-transform: uppercase;
  white-space: nowrap;
  overflow: hidden;
  position: relative;
  width: 100%;
  margin-top: 100px;
}

.A-B-C  span {
  font-size: 40px;
}

.message {
  background-color: yellow;
  display: block;
  font-weight: 900;
  overflow: hidden;
  position: absolute;
  left: 1170px;
  animation: openclose 5s ease-in-out infinite;
}

.word1, .word2, .word3 {
  font-family: tahoma;
}

@keyframes openclose {
  0% {
    top: 0.2rem;
    width: 0;
  }
  5% {
    width: 0;
  }
  15% {
    width: 230px;
  }
  30% {
    top: 0.2rem;
    width: 300px;
  }
  33% {
    top: 0.2rem;
    width: 0;
  }
  35% {
    top: 0.2rem;
    width: 0;
  }
  38% {
    top: -4.5rem;
    
  }
  48% {
    top: -4.5rem;
    width: 190px;
  }
  62% {
    top: -4.5rem;
    width: 250px;
  }
  66% {
    top: -4.5rem;
    width: 0;
    text-indent: 0;
  }
  71% {
    top: -9rem;
    width: 0;
    text-indent: 5px;
  }
  86% {
    top: -9rem;
    width: 285px;
  }
  95% {
    top: -9rem;
    width: 285px;
  }
  98% {
    top: -9rem;
    width: 0;
    text-indent: 5px;
  }
  100% {
    top: 0;
    width: 0;
    text-indent: 0;
  }
}
</style>
