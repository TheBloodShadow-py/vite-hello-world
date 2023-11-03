<script lang="ts">
import AppHero from "./components/AppHero.vue";
export default {
  data() {
    return {
      msg: "La mia prima app con Vue",
    };
  },
  components: { AppHero },
};
</script>

<template>
  <AppHero />
  <div>
    <span>{{ msg }}</span>
  </div>
</template>

<style scoped>
div {
  margin-top: 20px;
  display: flex;
  justify-content: center;
}
</style>
