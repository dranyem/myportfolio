<template>
  <div
    id="contact"
    class="container d-flex align-items-center justify-content-center"
  >
    <div
      class="row d-flex text-center"
      id="animateCn"
      style="opacity: 0; transform : scale(0.5); transition: all 1.5s ease-out;"
    >
      <div class="col">
        <h3 class="display-4 mb-4" style="font-family: Oxanium">
          Contact Information
        </h3>
      </div>
      <div class="w-100"></div>
      <div class="col">
        <p>
          Need to contact me? You can reach me out here:
          <a href="mailto:davidmeynard@yahoo.com.ph"
            >davidmeynard@yahoo.com.ph</a
          >
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
          <a href="https://www.linkedin.com/in/meynarddavid/">LinkedIn</a>.
        </p>
      </div>
      <div class="w-100"></div>
      <div class="col">
        Looking to hire? Here is my
        <a
          class="isDisabled"
          :href="this.publicPath + 'MeynardDavid-Resume.pdf'"
          download
          >resume</a
        >. <i>Resume Unavailable right now.</i>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      publicPath: process.env.BASE_URL,
    };
  },
  mounted() {
    const scene2 = this.$scrollmagic
      .scene({
        triggerElement: "#contact",
      })
      .setTween("#animateCn", {
        css: {
          opacity: 1,
          transform: "none",
        },
      });
    this.$scrollmagic.addScene(scene2);
  },
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
.isDisabled {
  color: currentColor;
  cursor: not-allowed;
  opacity: 0.5;
  text-decoration: none;
}
</style>
