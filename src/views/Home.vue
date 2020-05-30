<template>
  <div class="home">
    <Header />
    <Carousel />
  </div>
</template>

<script>
// @ is an alias to /src
import Header from "@/components/Header.vue";
import Carousel from "@/components/Carousel";

export default {
  name: "Home",
  components: {
    Header,
    Carousel
  }
};
</script>
