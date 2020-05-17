<template>
  <div class="projects">
    <Navigation activeLink="projects" />
    <StockTrackerProject />
    <TweeterProject />
    <OkotoksPizzaProject />
    <MyPortfolio />
  </div>
</template>

<script>
import Navigation from "../components/Navigation.vue";
import StockTrackerProject from "../components/StockTrackerProject.vue";
import TweeterProject from "../components/TweeterProject.vue";
import OkotoksPizzaProject from "../components/OkotoksPizzaProject.vue";
import MyPortfolio from "../components/MyPortfolio.vue";
export default {
  name: "Projects",
  components: {
    Navigation,
    StockTrackerProject,
    TweeterProject,
    OkotoksPizzaProject,
    MyPortfolio
  }
};
</script>
 <style scoped>
</style>