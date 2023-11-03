<script lang="ts">
import imageSrc from "../assets/sunset.jpeg";

export default {
  data() {
    return {
      imageSrc,
    };
  },
};
</script>

<template>
  <img :src="imageSrc" />
</template>

<style scoped>
img {
  height: 600px;
  width: 100%;
  object-fit: cover;
}
</style>
