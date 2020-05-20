<template>
  <div
    class="container d-flex align-items-center"
    style="height:100vh;"
    id="introduction"
  >
    <div
      class="row border-right border-left border-light"
      id="animateInt"
      style="opacity: 0; transform : scale(0.5); transition: all 1.5s ease-out;"
    >
      <div class="col-md-4 d-flex align-items-center justify-content-center">
        <img src="../assets/myimage.jpg" class="rounded d-block shadow" />
      </div>
      <div class="col-md-8 my-4">
        <p>Hey there!</p>
        <p>
          My name is
          <strong style="font-family: Oxanium">Meynard David</strong>, and I am
          a developer based in Calgary, AB. I just finished a Full Stack Web
          Development program from InnoTech College and is actively looking for
          a position in this field.
        </p>
        <p>
          I love solving problems. Whether it’s finding the most elegant way to
          write a line of code or figuring out the most efficient way to
          implement something, I love the challenge of finding a way and
          discovering solutions.
        </p>
        <p class="text-center mt-5">
          <i class="fas fa-arrow-down"></i>
          Scroll down for more information
        </p>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Introduction",
  mounted() {
    const scene2 = this.$scrollmagic
      .scene({
        triggerElement: "#introduction",
      })
      .setTween("#animateInt", {
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
p {
  font-size: larger;
  font-family: Muli;
}
</style>
