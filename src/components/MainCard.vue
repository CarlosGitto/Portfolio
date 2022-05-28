<template>
  <div class="row background-color-black-portfolio">
      <div class="col-7">
          <div>
              <h1 class="text-color-light-grey-portfolio">Carlos Ismael Gitto Bernales</h1>
          </div>
          <div><span class="text-color-light-grey-portfolio"> FullStack Software Developer</span></div>
          <div><p class="text-color-light-grey-portfolio">Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit sem pharetra id posuere a egestas amet. Vitae interdum eu amet purus, vitae dis accumsan tortor at.</p></div>
        <div>
            <font-awesome-icon class="text-color-light-grey-portfolio fs-1" :icon="['fab','linkedin-in']" />
            <font-awesome-icon class="text-color-light-grey-portfolio fs-1" :icon="['fab','github']" />
        </div>
      </div>

      <div id="main-card-second-box" class="col-5 background-color-light-grey-portfolio"
>
          
        <font-awesome-icon class="text-white fs-1" icon="circle" />
      </div>

  </div>
</template>

<script>
export default {
    name: "MainCard",

}
</script>

<style scoped>
#main-card-second-box{
     border-left-width: 20px;
  border-left-style: solid;
  border-left-color:#3ED7B4;

}
</style>