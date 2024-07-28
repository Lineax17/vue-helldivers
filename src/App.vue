<template>
  <Header></Header>
  <StratagemImage :imagePath="require('./assets/stratagems/bridge/Tesla_Tower.svg')"></StratagemImage>
</template>

<script>

import Header from "@/components/Header.vue";
import StratagemImage from "@/components/StratagemImage.vue";

export default {
  name: 'App',
  components: {
    StratagemImage,
    Header
  }
}
</script>

<style>
body {
  background-color: black;
  font-family: "Calibri",serif;
  color: white;
}
</style>