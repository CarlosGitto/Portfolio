<template>
  <div id="main-projects-card" class="row background-color-black-portfolio">
      <div class=" col-1 background-color-light-grey-portfolio">
          <font-awesome-icon class="text-white fs-1" icon="circle" />
          <span class="text-color-black-portfolio">box1</span>
          <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
      <div class="col-1 background-color-light-grey-portfolio">
          <font-awesome-icon class="text-white fs-1" icon="circle" />
          <span class="text-color-black-portfolio">box2</span>
          <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
      <div class="col-1 background-color-light-grey-portfolio">
          <font-awesome-icon class="text-white fs-1" icon="circle" />
          <span class="text-color-black-portfolio">box3</span>
          <p class="text-center">Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor.</p>
      </div>
      <span class="text-color-light-grey-portfolio">Para un servicio perzonalizado <a href="#">click aqui</a></span>
  </div>
</template>

<script>
export default {
 name: "MainProjectsCard",

}
</script>

<style scoped>
#main-projects-card{

     border-bottom-width: 20px;
  border-bottom-style: solid;
  border-bottom-color:#3ED7B4;

}
</style>