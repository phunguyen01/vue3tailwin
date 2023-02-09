<template>
  <up />
  <down />
</template>
<script>
import up from "./components/Up.vue";
import down from "./components/Down.vue";

export default {
  name: "App",
  components: {
    up,
    down,
  },
};
</script>

<style>
</style>
