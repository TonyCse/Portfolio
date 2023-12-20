<template>
  <h2 class="exp-title my-16">Experiences professionnelles et formations</h2>
  <h3 class="d-flex justify-start title-card">Experience professionnelles</h3>
      <div class="card">
        <div class="date">
          Sept 2022 - Mar 2023
        </div>
        <div class="body-card">
          <div class="title-card mb-3">
            Stage Développeur Front-End · Habiteo · Paris
          </div>
          <div class="description-card mb-3">
            Développer et optimiser l'ergonomie et la navigation de 3 applications web pour une start-up spécialisée dans l'innovation immobilière 3D.
          </div>
          <div class="footer-card">
            <span class="tag">HTML/CSS/SCSS</span>
            <span class="tag">JavaScript</span>
            <span class="tag">Nodes.js</span>
            <span class="tag">Vue.js</span>
            <span class="tag">Vuetify</span>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="date">
          Sept 2015 - Août 2022
        </div>
        <div class="body-card">
          <div class="title-card mb-3">
            Agent de sécurité · Procedo · Paris
          </div>
          <div class="description-card mb-3">
            Contrôler et surveiller les accès d'un data center du ministère des finances.
          </div>
        </div>
      </div>
      <h3 class="d-flex justify-start title-card">Formation</h3>
      <div class="card">
        <div class="date">
          2023 - 2025
        </div>
        <div class="body-card">
          <div class="title-card mb-3">
            Bac +4 Développeur Full Stack en alternance · Cloud Campus · Paris
          </div>
          <div class="description-card mb-3">
            Cloud Campus https://cloud-campus.fr/
          </div>
          <div class="footer-card">
            <span class="tag">Figma</span>
            <span class="tag">React.js</span>
            <span class="tag">PHP</span>
            <span class="tag">Laravel</span>
            <span class="tag">Docker</span>
          </div>
        </div>
      </div>
      <div class="card">
        <div class="date">
          Oct 2021 - Avril 2022
        </div>
        <div class="body-card">
          <div class="title-card mb-3">
            Bac +2 Développeur web · Openclassrooms · Paris
          </div>
          <div class="description-card">
            <p class="mb-3">
              Transformer une maquette en page web HTML/CS
            </p>
            <p class="mb-3">
              Analyser et optimiser le SEO d'une application web
            </p>
            <p class="mb-3">
              Créer un site d'e-commerce en JavaScript Vanilla
            </p>
            <p class="mb-3">
              Construire une API sécurisée via JWT
            </p>
            <p class="mb-3">
              Créer un réseau social d'entreprise avec Express.js et Vue.js
            </p>
          </div>
          <div class="footer-card">
            <span class="tag">HTML/CSS</span>
            <span class="tag">JavaScript</span>
            <span class="tag">Nodes.js</span>
            <span class="tag">Express.js</span>
            <span class="tag">Sequelize</span>
            <span class="tag">Mongoose</span>
            <span class="tag">Vue.js</span>
            <span class="tag">Vuetify</span>
            <span class="tag">Bootstrap</span>
            <span class="tag">MongoDB</span>
            <span class="tag">MYSQL</span>
          </div>
        </div>
      </div>
</template>


<script>
export default {
  name: 'ExperienceVue',
}
</script>

<style scoped>

.exp-title{
      display: flex;
      text-align: left;
    }
    .exp-title::before{
    content: "02.";
    margin-right: 10px;
    color: var(--green);
    }
    .exp-title:after{
      content: "";
    display: block;
    position: relative;
    top: 20px;
    width: 300px;
    height: 1px;
    margin-left: 20px;
    background-color: white;
    }

.card{
  display: flex;
  padding: 30px 30px 30px 5px;
}

.card:hover{
  background-color: rgba(91, 177, 171, 0.11);
  border-radius: 5px;
  width: 98%;
}
.date{
  width: 20%;
  font-size: 15px;
  color: rgb(168, 168, 168);
  font: 1em "Anonymous Pro";
      font-weight: 900;
}

.body-card{
  padding: 0px 30px;
  display: flex;
  flex-direction: column;
  align-items:flex-start;
}
.title-card{
  color: rgb(255, 255, 255);
  font: 1.4em "Anonymous Pro";
      font-weight: 900;
}
.description-card{
  text-align: left;
  font: 1em "Anonymous Pro";
      font-weight: 900;
}

.footer-card{
  margin: 10px 0px;
}

.tag{
  margin-right: 10px;
  font-weight: bolder ;
  border-radius: 15px;
  padding: 3px 7px;
  background-color: rgb(91, 177, 171);
  color: black;
}

.pdf{
  margin: 0px 325px;
  width: 10%;
  font-weight: bolder;
  color: black;
  text-decoration: none;
  border-radius: 15px;
  background-color: rgb(91, 177, 171);
}
</style>