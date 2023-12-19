<template>
  <router-view/>
</template>

<style>
  @import url('https://fonts.googleapis.com/css2?family=Anonymous+Pro:ital,wght@0,400;0,700;1,400;1,700&family=Archivo+Black&display=swap');
#app {
  font-family: 'Anonymous Pro', 'Archivo Black','Avenir', Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: rgb(255, 255, 255);
}
body{
  background-color: #333A6D;
  margin: 50px;
  padding: 40px;
}

</style>

<script>
    export default {
        name: 'app',
        created () {
            document.title = "Tony Cseresznyak";
        }
    }
</script>