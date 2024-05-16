<script lang="ts">
import Banner from './components/Banner.vue';
import ConteudoPrincipal from './components/ConteudoPrincipal.vue';

export default {
  components: { Banner, ConteudoPrincipal } // quando o nome da propriedade é igual ao seu valor, podemos deixar só um { Banner: Banner } 
}
</script>

<template>
  <Banner />
  <ConteudoPrincipal />
</template>

<style scoped>

</style>

