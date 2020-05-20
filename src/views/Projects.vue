<template>
  <div class="projects" id="pinContainer">
    <Navigation activeLink="projects" />
    <StockTrackerProject class="panel st" />
    <TweeterProject class="panel tw" />
    <OkotoksPizzaProject class="panel op" />
    <MyPortfolio class="panel mp" />
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
    MyPortfolio,
  },
  mounted() {
    var slides = document.querySelectorAll(".panel");
    for (var i = 0; i < slides.length; i++) {
      var scene2 = this.$scrollmagic
        .scene({
          triggerElement: slides[i],
          triggerHook: "onLeave",
        })
        .setPin(slides[i], { pushFollowers: false });
      this.$scrollmagic.addScene(scene2);
    }
  },
};
</script>
<style scoped></style>
