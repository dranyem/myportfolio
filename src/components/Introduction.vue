<template>
  <div class="container d-flex align-items-center" style="height:100vh;">
    <div class="row border-right border-left border-light">
      <div class="col-md-4 d-flex align-items-center justify-content-center">
        <img src="../assets/myimage.jpg" class="rounded d-block shadow" />
      </div>
      <div class="col-md-8 my-4">
        <p>Hey there!</p>
        <p>
          My name is
          <strong style="font-family: Oxanium">Meynard David</strong>,
          and I am Calgary, AB based developer. I just finished a Full Stack Web Development program from InnoTech College and is actively looking for a position in this field.
        </p>
        <p>I love solving problems. Whether it’s finding the most elegant way to write a line of code or figuring out the most efficient way to implement something, I love the challenge of finding a way and discovering solutions.</p>
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
  name: "Introduction"
};
</script>

<style scoped>
p {
  font-size: larger;
  font-family: Muli;
}
</style>