<template>
  <div class="projects">
    <Navigation activeLink="projects" />
    <StockTrackerProject />
    <TweeterProject />
    <OkotoksPizzaProject />
  </div>
</template>

<script>
import Navigation from "../components/Navigation.vue";
import StockTrackerProject from "../components/StockTrackerProject.vue";
import TweeterProject from "../components/TweeterProject.vue";
import OkotoksPizzaProject from "../components/OkotoksPizzaProject.vue";
export default {
  name: "Projects",
  components: {
    Navigation,
    StockTrackerProject,
    TweeterProject,
    OkotoksPizzaProject
  }
};
</script>
 <style scoped>
</style>