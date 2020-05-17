<template>
  <div class="container-fluid d-flex justify-content-center align-items-center">
    <div class="row w-100">
      <div class="col-md-6">
        <div id="carouselExampleIndicator2" class="carousel slide w-100 h-100" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicator2" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="3"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="4"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="5"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="6"></li>
            <li data-target="#carouselExampleIndicator2" data-slide-to="7"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/tweeter/tw-0.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-1.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-2.png" class="d-block w-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-3.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-4.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-5.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-6.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/tweeter/tw-7.png" class="d-block w-100 mh-100" alt />
            </div>
          </div>
          <a
            class="carousel-control-prev"
            href="#carouselExampleIndicator2"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExampleIndicator2"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <div class="col-md-6 text-center mt-3">
        <p class="h1" style="font-family: Oxanium">Tweeter</p>
        <a class="btn btn-outline-light btn-sm mx-3" href="https://md-tweeter.ml/" target="_blank">
          Live
          <i class="fas fa-external-link-alt"></i>
        </a>
        <a
          class="btn btn-outline-light btn-sm mx-3"
          href="https://github.com/dranyem/Tweeter-Two"
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
          <i class="devicon-vuejs-plain-wordmark"></i>
          <br />
          <i>
            <img
              src="../assets/tweeter/bulma-logo.png"
              style="background-color: white; width:50px; height:30px"
              alt
            />
          </i>
          <i class="devicon-laravel-plain-wordmark colored"></i>
          <i class="devicon-php-plain colored"></i>
          <i class="devicon-mysql-plain-wordmark colored"></i>
        </div>
        <p class="m-3">
          A Twitter ripoff.
          A CRUD application that uses the Model-View-Controller design pattern. This project also uses
          <a
            href="https://giphy.com/"
          >Giphy API</a> and hosted on a google cloud web hosting server.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "TweeterProject"
};
</script>

<style scoped>
.container-fluid {
  font-family: Muli;
  min-height: 100vh;
  background-color: #00d1b2;
}
.logo i {
  font-size: 2.5em;
  margin: 0 5px;
}
</style>