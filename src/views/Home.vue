<template>
  <div>
    <Carousel />
    <Sobre_nosotros />
    <Como_comprar />
  </div>
</template>

<style scoped>
h4 {
  text-align: center;
}

p {
  text-align: justify;
}

small {
  text-align: center;
}
</style>

<script>
import Carousel from "../components/Carousel.vue";
import Como_comprar from "../components/Como_comprar.vue";
import Sobre_nosotros from "../components/Sobre_nosotros.vue";
export default {
  components: {
    Carousel,
    Como_comprar,
    Sobre_nosotros,
  },
};
</script>
