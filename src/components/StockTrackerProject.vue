<template>
  <div
    class="container-fluid d-flex justify-content-center align-items-center"
    style="height:100vh;"
  >
    <div class="row w-100">
      <div class="col-md-6">
        <div id="carouselExampleIndicator1" class="carousel slide w-100 h-100" data-ride="carousel">
          <ol class="carousel-indicators">
            <li data-target="#carouselExampleIndicator1" data-slide-to="0" class="active"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="1"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="2"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="3"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="4"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="5"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="6"></li>
            <li data-target="#carouselExampleIndicator1" data-slide-to="7"></li>
          </ol>
          <div class="carousel-inner">
            <div class="carousel-item active">
              <img src="../assets/stocktracker/st-0.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-1.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-2.png" class="d-block w-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-3.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-4.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-5.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-6.png" class="d-block w-100 mh-100" alt />
            </div>
            <div class="carousel-item">
              <img src="../assets/stocktracker/st-7.png" class="d-block w-100 mh-100" alt />
            </div>
          </div>
          <a
            class="carousel-control-prev"
            href="#carouselExampleIndicator1"
            role="button"
            data-slide="prev"
          >
            <span class="carousel-control-prev-icon" aria-hidden="true"></span>
            <span class="sr-only">Previous</span>
          </a>
          <a
            class="carousel-control-next"
            href="#carouselExampleIndicator1"
            role="button"
            data-slide="next"
          >
            <span class="carousel-control-next-icon" aria-hidden="true"></span>
            <span class="sr-only">Next</span>
          </a>
        </div>
      </div>
      <div class="col-md-6 text-center mt-3">
        <p class="h1" style="font-family: Oxanium">Stock Tracker</p>
        <a class="btn btn-outline-light btn-sm mx-3" href="https://stocktracker.ml" target="_blank">
          Live
          <i class="fas fa-external-link-alt"></i>
        </a>
        <a
          class="btn btn-outline-light btn-sm mx-3"
          href="https://github.com/dranyem/mvp-stocktracker"
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
        <p class="m-3">
          A simple Stock Tracking Website. Uses various API such as
          <a
            href="https://www.alphavantage.co/"
          >Alphantage</a>,
          <a href="https://iexcloud.io/">IEX Cloud</a>,
          <a href="https://newsapi.org/">News API</a> to provide data and information. This mvp project also uses VUEX for state management and hosted on a google cloud web hosting server.
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "StockTrackerProject"
};
</script>

<style scoped>
.container-fluid {
  font-family: Muli;
  min-height: 100vh;
  background-color: #424c6a;
}
.logo i {
  font-size: 2.5em;
  margin: 0 5px;
}
</style>