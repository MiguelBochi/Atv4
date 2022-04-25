<script>
import Rodape from "./components/Rodape.vue";
import Principal from "./components/Principal.vue";
import Cabecario from "./components/Cabecario.vue";
import MenuLateral1 from "./components/MenuLateral.vue";
export default {
  components: { Rodape, Principal, Cabecario, MenuLateral1 },
};
</script>
<template>
  <MenuLateral1 />
  <Cabecario />
  <Rodape />
  <Principal />
</template>
<style></style>
