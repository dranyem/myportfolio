<template>
  <div id="app">
    <!-- <div id="nav">
      <router-link to="/">Home</router-link>|
      <router-link to="/about">About</router-link>|
      <router-link to="/projects">Projects</router-link>
    </div>-->
    <router-view />
  </div>
</template>

<style>
body {
  background-color: rgb(5, 37, 56);
}
#app {
  height: 100vh;
  max-width: 100vw;
  color: white;
}
</style>
