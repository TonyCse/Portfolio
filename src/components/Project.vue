<template>
  <h2 class="project-title my-16">Mes projets</h2>
  <div class="container">
    <div class="d-flex mb-16">
      <a href="https://pokedex-tony-cseresznyak.vercel.app/">
        <img class="project-img" src="../assets/pokedex.png" alt="pokedex">
      </a>
      <div class="ml-10 d-flex card-title">
        <div>
          <h2 class>
            Pokedex
          </h2>
        </div>
        <div class="card-footer">
          <span>test</span>
        </div>
      </div>
      <div class="card-body">
        Un Pokedex first-gen réalisé sous Vue.JS en consommant l'API <a class="link" href="https://pokeapi.co/"> https://pokeapi.co/</a>. <br> Affichage des 151 premiers pokemon, récupération et affichage de l'image, de l'id et du type du pokemon selectionné.
      </div>
    </div>
    <div class="d-flex flex-row-reverse mb-16">
      <a href="https://pokedex-tony-cseresznyak.vercel.app/">
        <img class="project-img" src="../assets/pokedex.png" alt="pokedex">
      </a>
      <div class="ml-10 ">
        <p class="green"> Projet perso </p>
        <h2>
          Pokedex
        </h2>
      </div>
      <div>
        Un Pokedex first-gen réalisé sous Vue.JS en consommant l'API <a class="link" href="https://pokeapi.co/"> https://pokeapi.co/</a>. <br> Affichage des 151 premiers pokemon, récupération et affichage de l'image, de l'id et du type du pokemon selectionné.
      </div>
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
.project-title:before{
  content: "03.";
  margin-right: 10px;
  color: var(--green);
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

.card-title{
  text-align: left;
  display: flex;
  justify-content: space-between;
}
.card-body{
  max-height: 140px;
  max-width: 400px;
  background-color: #2c3366;
  text-align: left;
  padding: 10px;
  border-radius: 5px;
  position:relative;
  left: -190px;
  top: 80px;
}

.card-footer{
  display: flex;
  left: 1px;
  bottom: 2px;
}
</style>
