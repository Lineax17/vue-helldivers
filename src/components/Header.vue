<script>
export default {
  // eslint-disable-next-line vue/multi-word-component-names
  name: 'Header',
}
</script>

<template>
  <header>
    <img id="header_image" src="../assets/Helldivers_Icon.png">
    <br>
    <h1>Helldivers Stratagem Trainer</h1>
  </header>
</template>

<style scoped>
header {
  display: flex;
  background-color: #d09e05;
  height: 150%;
  margin: 20px;
  justify-content: center;
  align-items: center;
  flex-direction: column;
  color: black;
}

#header_image {
  width: 250px;
  height: 250px;
  margin-top: 3%;

}
</style>