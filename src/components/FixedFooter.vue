<template>
  <footer
    class="d-flex flex-row h-100 w-100 justify-content-between px-5 align-items-center py-5 background-secondary-color"
  >
    <div class="text-white">
      <a href="https://www.linkedin.com/in/carlosgitto/" target="_blank">
        <font-awesome-icon
          class="font-awesome-icon text-color-light-grey-portfolio fs-2 me-3"
          :icon="['fab', 'linkedin-in']"
        />
      </a>
      <a href="https://github.com/CarlosGitto" target="_blank">
        <font-awesome-icon
          class="font-awesome-icon text-color-light-grey-portfolio fs-2"
          :icon="['fab', 'github']"
      /></a>
    </div>
    <div>
      <span class="text-color-light-grey-portfolio"
        >Made by
        <a
          href="https://github.com/CarlosGitto"
          target="_blank"
          class="text-decoration-none text-color-green-portfolio"
          >@CarlosGitto</a
        >
        in 2022, Github</span
      >
    </div>
  </footer>
</template>

<script>
export default {
  name: "FixedFooter",
};
</script>

<style></style>
