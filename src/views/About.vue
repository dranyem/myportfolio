<template>
  <div class="about">
    <Navigation activeLink="about" />
    <Introduction />
    <Skills />
    <Contact />
  </div>
</template>

<script>
import Introduction from "../components/Introduction.vue";
import Navigation from "../components/Navigation.vue";
import Skills from "../components/Skills.vue";
import Contact from "../components/Contact.vue";
export default {
  name: "About",
  components: {
    Introduction,
    Navigation,
    Skills,
    Contact
  }
};
</script>

<style scoped>
</style>
