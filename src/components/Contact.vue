<template>
  <div id="contact" class="container d-flex align-items-center justify-content-center">
    <div class="row d-flex text-center">
      <div class="col">
        <h3 class="display-4 mb-4" style="font-family: Oxanium">Contact Information</h3>
      </div>
      <div class="w-100"></div>
      <div class="col">
        <p>
          Need to contact me? You can reach me out here:
          <a
            href="mailto:davidmeynard@yahoo.com.ph"
          >davidmeynard@yahoo.com.ph</a>
        </p>
      </div>
      <div class="w-100"></div>
      <div class="col">
        <p>
          Or give me a call
          <a href="tel:5872241716">587-224-1716</a>
        </p>
      </div>
      <div class="w-100"></div>
      <div class="col">
        <p>
          You could also contact me through
          <a
            href="https://www.linkedin.com/in/meynarddavid/"
          >LinkedIn</a>.
        </p>
      </div>
      <div class="w-100"></div>
      <div class="col">
        Looking to hire? Here is my
        <a
          :href="this.publicPath+'MeynardDavid-Resume.pdf'"
          download
        >resume</a>.
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      publicPath: process.env.BASE_URL
    };
  }
};
</script>

<style scoped>
.container {
  color: white;
  min-height: 100vh;
  background: rgb(5, 37, 56);
}
p {
  font-family: Muli;
}
</style>