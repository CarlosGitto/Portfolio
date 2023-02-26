<template>
  <main class="container-fluid m-0 p-0">
    <header>
      <FixedNavbar />
    </header>
    <router-view />
  </main>
  <FixedFooter />
</template>
<script>
import FixedNavbar from "./components/FixedNavbar.vue";
import FixedFooter from "./components/FixedFooter.vue";

export default {
  components: {
    FixedNavbar,
    FixedFooter,
  },
};
</script>

<style>
::-webkit-scrollbar {
  width: 1vw; /* for vertical scrollbars */
  height: 1vw; /* for horizontal scrollbars */
}

::-webkit-scrollbar-track {
  background: linear-gradient(180deg, var(--primary-color) 0%,  white 50%, var(--primary-color) 100%);
}

::-webkit-scrollbar-thumb {
  background: var(--secondary-color);
}
:root {
  --primary-color: #d9dbf1;
  --secondary-color: #2a3034;
  --accent-color: #3ed7b4;
}
body,
html {
  background-color: var(--primary-color) !important;
}

html {
  scroll-behavior: smooth !important;
}
section {
  width: 100% !important;
  min-height: 100vh !important;
}

a {
  color: var(--primary-color) !important;
}
.container-fluid {
  overflow: hidden;
}
.translucid-effect {
  border: 1px solid transparent;
  backdrop-filter: blur(0.3rem);
  border-bottom-color: rgba(225, 225, 225, 0.2) !important;
  background-color: rgba(225, 225, 225, 0.04) !important;
}
.text-primary-color {
  color: var(--primary-color) !important;
}
.text-secondary-color {
  color: var(--secondary-color) !important;
}
.text-accent-color {
  color: var(--accent-color) !important;
}

.background-primary-color {
  background-color: var(--primary-color) !important;
}
.background-secondary-color {
  background-color: var(--secondary-color) !important;
}
.background-accent-color {
  background-color: var(--accent-color) !important;
}

#app {
  font-family: "Source Sans Pro", sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
}

/*  */
</style>
