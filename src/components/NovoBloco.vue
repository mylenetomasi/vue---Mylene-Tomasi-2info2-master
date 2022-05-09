<script>
export default {
  // props: ["titulo"],
  props: {
    titulo: {
      default: "",
    },
    nomes: Array,
  },
};
</script>
<template>
  <article class="block">
    <h1>{{ titulo }}</h1>
  </article>
</template>
