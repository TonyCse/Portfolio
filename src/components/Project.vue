<template>
  <h2 class="project-title my-16">Mes projets</h2>
</template>

<script>
export default {
  name: 'ProjectVue',
}
</script>

<style scoped>
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
</style>
