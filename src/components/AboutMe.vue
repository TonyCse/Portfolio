<template>
      <div class="about">
          <h2 class="about-title my-16">À propos de moi</h2>
          <div class="d-flex">
            <img class="photo mr-10" src="../assets/photoCV.jpg" alt="photo">
            <p class="text">Bonjour ! Je m'appelle Tony, j'ai 29 ans et j'habite en région parisienne. <br> <br> En 2020, sur mon temps libre, je commence à me former en autodidacte au développement web et ça commence vraiment à me plaire, je me pose alors la question " Pourquoi ne pas en faire mon métier ? ".  <br> <br>Aimant depuis tout petit résoudre des casses-têtes et des énigmes me voilà aux anges devant toutes ces ERROR qui s'affichent dans ma console ( ça fait pas trop zinzin ça va ? ) <br><br> Je décide donc de laisser ces 7 années en tant qu'agent de sécu derrière moi et je me lance dans une formation où je ressors diplômé d'un bac+2 développeur web. Avance rapide jusqu'à aujourd'hui où ma priorité est de me former un maximum et de devenir un couteau Suisse du développement web. C'est pourquoi je cherche actuellement une alternance afin de décrocher dans un premier temps le bac+4 développeur full-stack et ensuite le bac+5 expert en cybersécurité ( la continuité d'agent de sécu mais dans un ordinateur au final non ? ). <br><br> Quand je ne suis pas devant VSCode j'essaye tant bien que mal de me hisser en haut du ladder de ce jeu tellement reposant et zen qu'est LEAGUE OF LEGENDS, sinon je joue à des triples A tels que Avatar: Frontiers of Pandora, Cyberpunk 2077, Marvel's Spider-Man.  </p>
          </div>
      </div>
</template>
    
    <script>
    export default {
      name: 'AboutMe',
      props: {
        msg: String
      }
    }
    </script>
    
    <!-- Add "scoped" attribute to limit CSS to this component only -->
    <style scoped>
 

    .text{
      font: 1.4em "Anonymous Pro";
      font-weight: 900;
      text-align: left;
      width: 60%;
      line-height: 1.4;
    }
    .about{
      min-height: 800px;
    }
    .about-title{
      display: flex;
      text-align: left;
    }
    .about-title::before{
    content: "01.";
    margin-right: 10px;
    color: var(--green);
    }
    .about-title:after{
    content: "";
    display: block;
    position: relative;
    top: 20px;
    width: 300px;
    height: 1px;
    margin-left: 20px;
    background-color: white;
    }
    .photo{
      width: 200px;
      height: 200px;
      border-radius: 100px;
    }
    </style>