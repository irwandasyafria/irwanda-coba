<template>
  <div class="home">
    <img alt="Vue logo" src="../assets/foto1.jpg" />
    <Kalkulator msg="Irwanda Syafriadi" />
  </div>
</template>

<script>
// @ is an aWlias to /src
import Kalkulator from "@/components/Kalkulator.vue";

export default {
  name: "Home",
  components: {
    Kalkulator,
  },
};
</script>