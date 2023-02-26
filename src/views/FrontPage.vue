<template>
  <section
    class="d-flex flex-row background-gradient-section padding-for-top-bar px-5"
    id="main-section"
  >
    <div class="py-5">
      <MainCard />
    </div>
  </section>
  <section id="activity-section" class="">
    <div class="">
      <div class="background-gradient-section padding-for-top-bar w-100"></div>
      <MainProjectsCard id="main-project-cards" class="px-5" />
      <ActivityCard />
    </div>
  </section>

  <section id="contact-section" class="d-flex flex-column">
    <div class="">
      <div class="background-gradient-section padding-for-top-bar w-100"></div>

      <ContactCard class="py-5 px-5" />
    </div>
  </section>
</template>

<script>
import MainCard from "@/components/MainCard.vue";
import MainProjectsCard from "@/components/MainProjectsCard.vue";
import ContactCard from "@/components/ContactCard.vue";
import ActivityCard from "@/components/ActivityCard.vue";

export default {
  name: "FrontPage",
  components: {
    MainCard,
    MainProjectsCard,
    ContactCard,
    ActivityCard,
  },
};
</script>

<style>
.padding-for-top-bar {
  padding-top: 10vh !important;
}
/* .background-main-section {
  background:
 linear-gradient(
      90deg,
      var(--secondary-color),
      var(--secondary-color) 55%,
      var(--accent-color),
      var(--accent-color) 10%,
      var(--primary-color)    );
} */
.background-gradient-section {
  background: linear-gradient(
    90deg,
    var(--secondary-color),
    var(--accent-color) 100%,
    var(--primary-color) 100%
  );
}
</style>
