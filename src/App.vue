<template>
  <div id="app">
    <router-view id="view" style="background-color: rgb(5, 37, 56, .90);" />
  </div>
</template>

<style>
body {
  background-color: rgb(5, 37, 56);
  background-image: url("assets/home/pic3.jpg");
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
}
#app {
  height: 100vh;
  max-width: 100vw;
  color: white;
}
</style>
