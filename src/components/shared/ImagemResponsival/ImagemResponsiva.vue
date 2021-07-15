<template>
  <img class="imagem-responsiva" :src="url" :alt="titulo" />
</template>

<script>
export default {
  props: ["url", "titulo"],
};
</script>

<style scoped>
.imagem-responsiva {
  width: 100%;
}
.imagem-responsiva:hover {
  opacity: 0.8;
  transition-delay: 700;
}
</style>
