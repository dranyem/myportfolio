<template>
  <div>
    <nav class="navbar navbar-dark bg-dark navbar-expand-lg fixed-top">
      <router-link class="navbar-brand" to="/">
        <img
          src="https://media.giphy.com/media/Jp4zBl0aEoY3ScwmB3/giphy.gif"
          width="30px"
          height="30px"
          class="d-inline-block"
        />
        <h4
          class="text-uppercase d-inline-block text-light mb-0"
          style="font-family: Audiowide"
        >Meynard David</h4>
      </router-link>
      <button
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNav"
        aria-controls="navbarNav"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNav">
        <ul class="navbar-nav text-center" style="font-family: Oxanium">
          <li class="nav-item">
            <router-link class="nav-link" to="/">Home</router-link>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="#">My Projects</a>
          </li>
          <li class="nav-item active">
            <router-link class="nav-link" to="/about">About Me</router-link>
          </li>
          <li class="nav-item">
            <div class>
              <a
                class="logo text-muted h3 px-2 align-bottom"
                href="https://www.linkedin.com/in/meynarddavid/"
                target="_blank"
              >
                <i class="fab fa-linkedin"></i>
              </a>
              <a
                class="logo text-muted h3 px-2 align-bottom"
                href="https://github.com/dranyem"
                target="_blank"
              >
                <i class="fab fa-github"></i>
              </a>

              <a
                class="logo text-muted h3 px-2 align-bottom"
                href="mailto:davidmeynard@yahoo.com.ph"
                target="_blank"
              >
                <i class="fas fa-id-card"></i>
              </a>
            </div>
          </li>
        </ul>
      </div>
    </nav>
    <!-- <div style="height: 1500px; background-color: pink"></div> -->
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
i:hover {
  color: white;
}
</style>