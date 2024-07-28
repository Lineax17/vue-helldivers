<script>
export default {
  name: 'StratagemImage',
  props: {
    imagePath: {
      type: String,
      required: true,
    }
  }
}
</script>

<template>
  <img :src="imagePath" alt="image">
</template>

<style scoped>
img {
  width: 150px;
  height: 150px;
}
</style>