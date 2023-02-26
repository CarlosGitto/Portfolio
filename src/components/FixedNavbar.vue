<template>
  <nav
    id="top-header"
    class="navbar shadow fixed-top navbar-expand-lg translucid-background"
  >
    <div class="d-flex justify-content-center collapse navbar-collapse">
      <ul
        class="d-flex justify-content-around w-100 align-items-center navbar-nav"
      >
        <li class="nav-item w-25"></li>
        <li class="nav-item me-5">
          <a
            class="nav-link text-decoration-none fw-bold"
            :class="{ 'text-secondary-color': isActive.mainSection }"
            aria-current="page"
            href="#main-section"
            >About</a
          >
        </li>
        <li class="nav-item me-5">
          <a
            class="nav-link text-decoration-none fw-bold"
            :class="{ 'text-secondary-color': isActive.activitySection }"
            href="#activity-section"
            >Feed</a
          >
        </li>
        <li class="nav-item me-5">
          <a
            class="nav-link text-decoration-none fw-bold"
            :class="{ 'text-secondary-color ': isActive.contactSection }"
            href="#contact-section"
            >Contact me</a
          >
        </li>
      </ul>
    </div>
  </nav>
</template>

<script>
export default {
  name: "FixedNavbar",
  data() {
    return {
      isActiveSearch: false,
      isActive: {
        mainSection: true,
        activitySection: false,
        contactSection: false,
      },
    };
  },
  computed: {
    mustFade(){
      return 0
    }
  }
};
</script>

<style scoped>


#top-header {
  height: 10vh !important;
}
.translucid-background {
  border: 1px solid transparent;
  backdrop-filter: blur(0.3rem);
  border-bottom-color: rgba(225, 225, 225, 0.2) !important;
  background-color: rgba(225, 225, 225, 0.04) !important;
}
li:after {
  display: block;
  content: "";
  border-bottom: solid 2px var(--primary-color);
  transform: scaleX(0);
  transition: transform 250ms ease-in-out;
}
li:hover:after {
  transform: scaleX(1);
}
</style>
