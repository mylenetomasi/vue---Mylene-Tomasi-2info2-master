<script>
import NovoBloco from "./NovoBloco.vue";
export default {
  components: { NovoBloco },
  data() {
    return {
      professores: ["", "", ""],
    };
  },
};
</script>
<template>
  <main id="content">
    <NovoBloco titulo="" />
    <NovoBloco titulo="" :nomes="professores" />
    <NovoBloco class="" />
    <NovoBloco class="" />
    <NovoBloco />
  </main>
</template>
<style></style>
