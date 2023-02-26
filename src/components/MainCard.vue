<template>
  <div class="row h-100">
    <div class="col-8 px-5">
      <div class="d-flex flex-row justify-content-center h-100 w-100">
        <div class="d-flex flex-column justify-content-center">
          <div>
            <h1 class="fw-bold text-start text-primary-color">
              Carlos Ismael Gitto Bernales
            </h1>
          </div>
          <div class="text-end">
            <span class="fs-4 text-primary-color"> Software Developer</span>
          </div>
          <div class="text-start">
            <p class="fw-light text-primary-color">
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. Donec sit
              sem pharetra id posuere a egestas amet. Vitae interdum eu amet
              purus, vitae dis accumsan tortor at.
            </p>
          </div>
          <div class="text-start">
            <a href="https://www.linkedin.com/in/carlosgitto/" target="_blank">
              <font-awesome-icon
                class="font-awesome-icon text-primary-color ms-2 me-4 fs-1"
                :icon="['fab', 'linkedin-in']"
              />
            </a>
            <a href="https://github.com/CarlosGitto" target="_blank">
              <font-awesome-icon
                class="font-awesome-icon text-primary-color fs-1"
                :icon="['fab', 'github']"
              />
            </a>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "MainCard",
};
</script>

<style scoped>
.border-accent {
  border-right: 1.56vw solid #3ed7b4 !important;
}
</style>
