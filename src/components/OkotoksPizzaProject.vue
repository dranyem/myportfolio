<template>
  <div
    class="container-fluid d-flex justify-content-center align-items-center"
    style="height:100vh;"
  >
    <div id="trigger3"></div>
    <div class="row w-100" id="reveal3">
      <div class="col-md-6">
        <div
          id="carouselExampleIndicator3"
          class="carousel slide w-100 h-100"
          data-ride="carousel"
        >
          <ol class="carousel-indicators">
            <li
              data-target="#carouselExampleIndicator3"
              data-slide-to="0"
              class="active"
            ></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="3"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="4"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="5"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="6"></li>
            <li data-target="#carouselExampleIndicator3" data-slide-to="7"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img
                src="../assets/okotokspizza/op-0.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-1.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-2.png"
                class="d-block w-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-3.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-4.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-5.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-6.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
            <div class="carousel-item">
              <img
                src="../assets/okotokspizza/op-7.png"
                class="d-block w-100 mh-100"
                alt
              />
            </div>
          </div>
          <a
            class="carousel-control-prev"
            href="#carouselExampleIndicator3"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExampleIndicator3"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <div class="col-md-6 text-center mt-3">
        <p class="h1" style="font-family: Oxanium">Okotoks Pizza</p>
        <a
          class="btn btn-outline-light btn-sm mx-3"
          href="https://okotokspizza.ml"
          target="_blank"
        >
          Live
          <i class="fas fa-external-link-alt"></i>
        </a>
        <a
          class="btn btn-outline-light btn-sm mx-3"
          href="https://github.com/dranyem/OkotoksPizza"
          target="_blank"
        >
          Source Code
          <i class="fas fa-code"></i>
        </a>
        <div class="logo mt-3">
          <p style="font-size:.9em;">
            Programming Language, Tools and Framework used:
          </p>
          <i class="devicon-html5-plain-wordmark colored"></i>
          <i class="devicon-css3-plain-wordmark colored"></i>
          <i class="devicon-sass-original colored"></i>
        </div>
        <p class="m-3">
          Okotoks Pizza Restaurant's website. A simple website for a pizza
          business restaurant. Implemented using plain HTML and CSS with Sass.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "OkotoksPizzaProject",
  mounted() {
    var scene = this.$scrollmagic
      .scene({
        triggerElement: "#trigger3",
        triggerHook: 0.9, // show, when scrolled 10% into view
        duration: "80%", // hide 10% before exiting view (80% + 10% from bottom)
        offset: 50, // move trigger to center of element
      })
      .setClassToggle("#reveal3", "visible"); // add class to reveal
    this.$scrollmagic.addScene(scene);
  },
};
</script>

<style scoped>
.container-fluid {
  font-family: Muli;
  min-height: 100vh;
  background-color: #d6b891;
}
.logo i {
  font-size: 2.5em;
  margin: 0 5px;
}
#reveal3 {
  opacity: 0;
  -webkit-transform: scale(0.6);
  -moz-transform: scale(0.6);
  -ms-transform: scale(0.6);
  -o-transform: scale(0.6);
  transform: scale(0.6);
  -webkit-transition: all 1.5s ease-in-out;
  -moz-transition: all 1.5s ease-in-out;
  -ms-transition: all 1.5s ease-in-out;
  -o-transition: all 1.5s ease-in-out;
  transition: all 1.5s ease-in-out;
}
#reveal3.visible {
  opacity: 1;
  -webkit-transform: none;
  -moz-transform: none;
  -ms-transform: none;
  -o-transform: none;
  transform: none;
}
</style>
