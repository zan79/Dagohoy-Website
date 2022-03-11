<template>
<LandingPage/>

</template>

<script>
import LandingPage from "./components/LandingPage.vue";

export default {
  name: "App",
  components: {
    LandingPage,
  },
};
</script>

<style>
body{
  background-repeat: no-repeat;
  background-size: cover;
  background-image: url("assets/background.png");
  image-rendering: auto;
  image-rendering: crisp-edges;
  image-rendering: pixelated;
  image-rendering: -webkit-optimize-contrast;
}
</style>
