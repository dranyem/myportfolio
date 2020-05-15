<template>
  <div class="about">
    <Navigation />
    <Introduction />
    <Skills />
  </div>
</template>

<script>
import Introduction from "../components/Introduction.vue";
import Navigation from "../components/Navigation.vue";
import Skills from "../components/Skills.vue";
export default {
  name: "About",
  components: {
    Introduction,
    Navigation,
    Skills
  }
};
</script>

<style scoped>
</style>
