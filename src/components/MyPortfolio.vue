<template>
  <div
    class="container-fluid d-flex justify-content-center align-items-center"
    style="height:100vh;"
  >
    <div class="row w-100">
      <div class="col-md-6">
        <div id="carouselExampleIndicator4" class="carousel slide w-100 h-100" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicator4" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicator4" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicator4" data-slide-to="2"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/home/h-1.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/home/h2.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/home/h3.png" class="d-block w-100" alt />
            </div>
          </div>
          <a
            class="carousel-control-prev"
            href="#carouselExampleIndicator4"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExampleIndicator4"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <div class="col-md-6 text-center mt-3">
        <p class="h1" style="font-family: Oxanium">This site. My portfolio</p>
        <a
          class="btn btn-outline-light btn-sm mx-3"
          href="https://github.com/dranyem/myportfolio"
          target="_blank"
        >
          Source Code
          <i class="fas fa-code"></i>
        </a>
        <div class="logo mt-3">
          <p style="font-size:.9em;">Programming Language, Tools and Framework used:</p>
          <i class="devicon-html5-plain-wordmark colored"></i>
          <i class="devicon-css3-plain-wordmark colored"></i>
          <i class="devicon-javascript-plain colored"></i>
          <i class="devicon-vuejs-plain-wordmark colored"></i>
          <i class="devicon-bootstrap-plain-wordmark"></i>
        </div>
        <p class="m-3">This site was made to showcase my projects and skill.</p>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.container-fluid {
  font-family: Muli;
  min-height: 100vh;
  background-color: #052538;
}
.logo i {
  font-size: 2.5em;
  margin: 0 5px;
}
</style>