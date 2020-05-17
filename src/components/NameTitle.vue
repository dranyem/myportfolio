<template>
  <div class="home">
    <div>
      <h3 class="font-weight-italic mb-2 text-center" style="font-family: Muli">Hi, I'm</h3>
    </div>
    <h1 class="text-uppercase display-4 text-center" style="font-family: Audiowide">Meynard David</h1>
    <div class="d-flex justify-content-center mt-2">
      <h4 class="font-weight-bold" style="font-family: Oxanium">
        <img
          src="https://media.giphy.com/media/Jp4zBl0aEoY3ScwmB3/giphy.gif"
          width="50px"
          height="50px"
        />
        Full Stack Web Developer
      </h4>
    </div>
    <div class="d-flex justify-content-between mt-4">
      <a
        class="btn btn-outline-light mx-auto"
        href="https://www.linkedin.com/in/meynarddavid/"
        target="_blank"
      >
        <i class="fab fa-linkedin" style="font-size: 1.5em"></i>
        <span class="d-none d-sm-inline pl-1">LinkedIn</span>
      </a>
      <a class="btn btn-outline-light mx-auto" href="https://github.com/dranyem" target="_blank">
        <i class="fab fa-github" style="font-size: 1.5em"></i>
        <span class="d-none d-sm-inline pl-1">GitHub</span>
      </a>

      <a class="btn btn-outline-light mx-auto" href="mailto:davidmeynard@yahoo.com.ph">
        <i class="fas fa-id-card" style="font-size: 1.5em"></i>
        <span class="d-none d-sm-inline pl-1">Contact</span>
      </a>
    </div>
    <div class="d-flex justify-content-center mt-4">
      <router-link
        class="text-light text-center m-3 h2 border-right border-left border-light px-2"
        style="font-family: Oxanium"
        to="/projects"
      >MY PROJECTS</router-link>
      <router-link
        class="text-light text-center m-3 h2 border-right border-left border-light px-2"
        style="font-family: Oxanium"
        to="/about"
      >ABOUT ME</router-link>
    </div>
  </div>
</template>

<script>
export default {
  name: "NameTitle",
  data() {
    return {
      bgImage: ""
    };
  },
  mount() {}
};
</script>

<style scoped>
</style>