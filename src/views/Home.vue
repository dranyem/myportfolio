<template>
  <div class="home d-flex align-items-center justify-content-center h-100">
    <NameTitle />
  </div>
</template>

<script>
import NameTitle from "../components/NameTitle.vue";
export default {
  name: "Home",
  components: {
    NameTitle,
  },
};
</script>
