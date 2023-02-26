<template>
  <div
    class="d-flex flex-column justify-content-center align-items-center background-color-black-portfolio"
  >
    <div class="d-flex flex-row w-75 px-5 justify-content-center h-100 my-4">
      <div
        v-for="index in 3"
        :key="index"
        class="d-flex flex-column translucid-effect justify-content-end me-4 p-2 rounded-lg border-end border-start"
      >
        <span>Webs{{ index }}</span>
        <p class="text-center mb-4 mx-3">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
          eiusmod tempor.
        </p>
      </div>
    </div>

    <div class="d-flex flex-row align-items-center w-100">
      <span class="text-secondary-color me-2"
        >Para un servicio perzonalizado
      </span>
      <span class="transform-test">
        <a href="#" class="text-decoration-none">click aqui</a>
        <font-awesome-icon
          class="font-awesome-icon ps-1 text-accent-color test"
          icon="arrow-right"
      /></span>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainProjectsCard",
};
</script>

<style>
.test {
  transition: all 0.3s;
  color: black;
  opacity: 0;
  transform: translateX(-20px);
  font-size: 12px;
}
.transform-test:hover .test {
  opacity: 1;
  transform: translateX(0px);
  color: aqua;
}
</style>
