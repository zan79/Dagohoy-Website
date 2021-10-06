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
  background: url('../src/assets/sda.png') no-repeat center center fixed;
  background-size: cover;
}
</style>
