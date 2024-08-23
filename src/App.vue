<template>
  <Header></Header>
  <StratagemSubsection></StratagemSubsection>
</template>


<script>

import Header from "@/components/Header.vue";
import StratagemSubsection from "@/components/StratagemSubsections.vue";

export default {
  name: 'App',
  components: {
    StratagemSubsection,
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