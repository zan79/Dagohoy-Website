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
html{

  background-repeat: no-repeat;
  background-size: cover;
  background: linear-gradient(rgb(255, 255, 255), rgb(207, 202, 205)),
  linear-gradient(white, white);
}
</style>
