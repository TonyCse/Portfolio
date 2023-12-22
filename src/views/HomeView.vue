<template>
  <body>
    <header class="header d-flex align-center justify-space-between ">
      <div class="logo-before">
        <img  class="logo" src="../assets/test.png" alt="logo">
      </div>
      <!-- <Glasses></Glasses> -->
      <nav class="d-flex">
          <p class="mx-5">01. À propos de moi</p>
        <p class="mx-5">02. Expériences professionnelles / Formations</p>
        <p class="mx-5">03. Mes projets</p>
      </nav>
    </header>
    <section class="section">
      <div class="mx-5 hello">
        <p class="mt-5 green text-size">Hello je m'appelle</p>
        <h1 class="text-h2 my-3 archivo">Tony Cseresznyak</h1>
        <h2 class="text-uppercase text-h4 green-2 archivo">Développeur Web</h2>
        <p class="text-sm-left my-8 text-size green"> Je suis un développeur web junior full stack avec un penchant pour le front et une forte sensibilité à l'UX/UI design. <br><br> Actuellement je suis en recherche d'une alternance pour mon bac+4 Développeur web full stack avec <a class=" keyword" href="https://cloud-campus.fr/developpeur-web-full-stack/"> Cloud Campus</a>.
        </p>
      </div>
        <a id="test">
          <AboutMe></AboutMe>
        </a>
        <ExperienceVue></ExperienceVue>
        <ProjectVue></ProjectVue>
    </section>
    <div class="social">
      <a href="https://github.com/TonyCse">
        <img class="social-logo" src="../assets/github.png" alt="github">
      </a>
      <a href="https://www.linkedin.com/in/tony-cseresznyak-b6b187230/">
        <img class="social-logo" src="../assets/linkedin.png" alt="linkedin">
      </a>
      <a href="https://www.youtube.com/@TonyCse/">
        <img class="social-logo" src="../assets/youtube.png" alt="youtube">
      </a>
    </div>
    <div class="side-mail">
      <div class="mail">
        <a class="vertical-mail" href="mailto:tonycseresznyak@hotmail.com"> tonycseresznyak@hotmail.com</a>
      </div>
    </div>
  </body>
</template>

<script>
// @ is an alias to /src
import AboutMe from '@/components/AboutMe.vue'
import ExperienceVue from '@/components/Experience.vue'
import ProjectVue from '@/components/Project.vue'


export default {
  name: 'HomeView',
  components: {
     AboutMe, ExperienceVue, ProjectVue
  }
}
</script>

<style scoped>

.text-size{
  font: 2em "Anonymous Pro";
}

.archivo{
  font: 4em 'Archivo Black' !important; 
}

.header{
  background-color: #2c3366;
  position:fixed;
  top: 0px;
  left: 0px;
  width: 100%;
  padding-top:30px;
  padding-bottom: 30px;
}
.social{
  display: flex;
  width: 40px;
  position: fixed;
  bottom: 70px;
  left: 40px;
  writing-mode: vertical-rl;
}
.social:after{
  content: "";
  position: fixed;
  bottom: 0px;
  left: 64px;
  width: 1px;
  height: 60px;
  margin: 0px auto;
  background-color: white;
}

.social-logo{
  height: 30px;
  width: 30px;
  margin-bottom: 20px;
}

.side-mail{
  width: 40px;
  position: fixed;
  bottom: 100px;
  right: 40px;
  z-index: 10;
}
.mail{
  margin: 20px auto;
    padding: 10px;
    writing-mode: vertical-rl;
}

.vertical-mail{
  text-decoration: none;
  color: rgb(91, 177, 171);
  font-size: larger;
  writing-mode: vertical-rl;
}
.vertical-mail:after{
  content: "";
  position: fixed;
  bottom: 0px;
  right: 57px;
    display: block;
    width: 1px;
    height: 100px;
    margin: 0px auto;
    background-color: white;
}
.logo{
  width: 100px;
  height: 100px;
  position: fixed;
  top: 0px;
  left: 90px;
}
.logo-before:before{
  content: "";
  position: fixed;
  top: 50px;
  left: 0px;
  width: 100px;
  height: 1px;
  margin: 0px auto;
  display: block;
  background-color: white;
}

.keyword{
  text-decoration:none;
  font-weight:700;
  color: white;
}
.green{
  color: rgb(91, 177, 171);
}
.green-2{
  color: rgb(134, 177, 174);
}
.aboutme:before{
  content: "01" ".";
  margin-right: 5px;
  color: rgb(91, 177, 171);
  text-align: right;
}

.section{
  padding: 0px 200px;
}
.hello{
  min-height: 1000px;
  justify-content: center;
  display: flex;
  flex-direction: column;
  align-items: flex-start;
}

</style>
