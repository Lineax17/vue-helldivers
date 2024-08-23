<script>
import { ref } from 'vue'
import stratagemData from '../../test.json'

const stratagems = ref(stratagemData.subsection["General Stratagems"].stratagems)

export default {
  name: 'TestJSON',
  setup() {
    return {
      stratagems
    }
  }
}
</script>

<template>
<div>
  <ul>
    <li v-for="stratagem in stratagems" :key="stratagem.name">
      {{ stratagem.name }}
    </li>
  </ul>
</div>
</template>

<style scoped>

</style>