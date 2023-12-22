<template>
  <h2 class="project-title my-16">Mes projets</h2>
  <div class="container">
    <div class="d-flex mb-16">
      <a href="https://pokedex-tony-cseresznyak.vercel.app/">
        <img class="project-img" src="../assets/pokedex.png" alt="pokedex">
      </a>
      <div class="ml-10 card-text">
        <h2 class="card-title">
          Pokedex
        </h2>
        <div class="card-footer">
          <a href="">
            <img class="logo" src="../assets/github-projet.png" alt="github">
          </a>
          <a href="">
            <img class="logo-link" src="../assets/link-projet.png" alt="link">
          </a>
          <a href="">
            <img class="logo" src="../assets/youtube-projet.png" alt="youtube">
          </a>
        </div>
      </div>
      <div class="card-body">
        Un Pokedex first-gen réalisé sous Vue.JS en consommant l'API <a class="link" href="https://pokeapi.co/"> https://pokeapi.co/</a>. <br> Affichage des 151 premiers pokemon, récupération et affichage de l'image, de l'id et du type du pokemon selectionné.
      </div>
    </div>
    <div class="d-flex flex-row-reverse mb-16">
      <a href="https://pokedex-tony-cseresznyak.vercel.app/">
        <img class="project-img" src="../assets/groupomania.png" alt="pokedex">
      </a>
      <div class="mr-10 card-text">
        <h2 class="card-title">
          Groupomania
        </h2>
        <div class="card-footer">
          <a href="">
            <img class="logo" src="../assets/github-projet.png" alt="github">
          </a>
          <a href="">
            <img class="logo-link" src="../assets/link-projet.png" alt="link">
          </a>
          <a href="">
            <img class="logo" src="../assets/youtube-projet.png" alt="youtube">
          </a>
        </div>
      </div>
      <div class="card-body-2">
        Groupomania est un réseau social d'entreprise avec lequel il est possible de : 
            <br> -Créer un compte avec un pseudo, un email et un mot de passe.
            <br> -Modifier son compte (son pseudo, son email, son mot de passe).
            <br> -Partager des posts avec ou sans média (jpeg,jpg,png,gif).
            <br> -Supprimer son compte et ses posts. <br> <br>
          <p> Un compte Admin est également présent, avec la possibilité de supprimer les posts des autres utilisateurs.</p>
      </div>
    </div>
    <div class="wip mt-10 pt-10">
      WORK IN PROGRESS
      Prochainement: la suite des projets réalisés (vidéo youtube démo), liens de la navbar cliquables qui renvoyent vers chaques sections associées, animations du logo et ajout d'une animation chargement à l'ouverture de la page.
    </div>
  </div>
</template>

<script>
export default {
  name: 'ProjectVue',
}
</script>

<style scoped>

.link{
  color: rgb(91, 177, 171);
  text-decoration: none;
}

.logo{
  width: 30px;
  height: 30px;
  margin: 20px;
}

.logo-link{
  width: 25px;
  height: 25px;
  margin: 5px;
}
.green{
  color: rgb(91, 177, 171);
}

.container{
  max-width: 70% ;
}
.project-title{
    display: flex;
    text-align: left;
}
.project-title:after{
  content: "";
  display: block;
  position: relative;
  top: 20px;
  width: 300px;
  height: 1px;
  margin-left: 20px;
  background-color: white;
}
.project-img{
  width: 500px;
  height: 400px;
  filter: grayscale(80%);
  border-radius: 5px;
}
.project-img:hover{
  filter: grayscale(0%);
}

.card-text{
  margin-top: 30px;
  text-align: left;
  display: flex;
  justify-content: space-between;
  flex-direction: column;
}

.card-title{
  font: 2.5em 'Archivo Black';
}

.card-body{
  max-height: 150px;
  min-width: 500px;
  background-color: #2c3366;
  text-align: left;
  padding: 10px;
  border-radius: 5px;
  position:relative;
  left: -260px;
  top: 100px;
}

.card-body-2{
  max-height: 220px;
  min-width: 600px;
  background-color: #2c3366;
  text-align: left;
  padding: 10px;
  border-radius: 5px;
  position:relative;
  left: 360px;
  top: 100px;
}

.card-footer{
  margin-bottom: 20px;
  display: flex;
  align-items: center;
  left: 1px;
  bottom: 2px;
  font: 1.4em "Anonymous Pro";
}
.wip{
  font: 2em "Anonymous Pro";
}
</style>
