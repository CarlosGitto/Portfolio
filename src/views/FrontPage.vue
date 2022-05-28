<template>
  <MainCard />
  <MainProjectsCard />
  <ActivityCard />
  <ContactCard />
</template>

<script>
import MainCard from '@/components/MainCard.vue'
import MainProjectsCard from '@/components/MainProjectsCard.vue'
import ContactCard from '@/components/ContactCard.vue'
import ActivityCard from '@/components/ActivityCard.vue'
export default {
 name: "FrontPage",
 components:{
    MainCard,
    MainProjectsCard,
    ContactCard,
    ActivityCard
}
}
</script>

<style>

</style>