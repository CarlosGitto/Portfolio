<template>
  <FixedNavbar />
  <router-view />
  <FixedFooter />
</template>
<script>
import FixedNavbar from './components/FixedNavbar.vue';
import FixedFooter from './components/FixedFooter.vue';

export default {
  components: {
    FixedNavbar,
    FixedFooter,
  },
}
</script>

<style>
body, html{
  background-color: #AFAFB0 !important;
}
.text-color-grey-portfolio{
  color: #AFAFB0 !important;
}
.text-color-light-grey-portfolio{
  color: #CFCED0 !important;
}
.text-color-green-portfolio{
  color: #3ED7B4 !important;
}
.text-color-black-portfolio{
  color: #2A3034 !important;
}

.background-color-grey-portfolio{
  background-color: #AFAFB0 !important;
}
.background-color-light-grey-portfolio{
  background-color: #CFCED0 !important;
}
.background-color-green-portfolio{
  background-color: #3ED7B4 !important;
}
.background-color-black-portfolio{
  background-color: #2A3034 !important;
}

.border-radius-12-portfolio{
  border-radius: 12px !important;
}

#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
}

#nav {
  padding: 30px;
}

#nav a {
  font-weight: bold;
  color: #2c3e50;
}

#nav a.router-link-exact-active {
  color: #42b983;
}
</style>
