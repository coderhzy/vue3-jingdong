<template>
  <div class="wrapper">
    <StaticPart />
    <Nearby />
  </div>
  <Docker />
</template>

<script lang="ts">
import Nearby from "../views/home/nearby/index.vue";
import Docker from "../views/home/docker/index.vue";
import StaticPart from "../views/home/StaticPart/index.vue";

export default {
  name: "Home",
  components: {
    Nearby,
    Docker,
    StaticPart,
  },
};
</script>

<style lang="scss">
.wrapper {
  overflow-y: auto;
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0.5rem;
  right: 0;
  padding: 0 0.18rem 0.1rem 0.18rem;
}
</style>
