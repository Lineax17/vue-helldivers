<script setup>
import { ref } from 'vue'
import stratagemData from '../../stratagems.json'

const subsections = ref(Object.keys(stratagemData.subsections))
</script>

<template>
  <div>
    <ul>
      <li v-for="subsection in subsections" :key="subsection">
        <h3>{{ subsection }}</h3>
        <ul>
          <li v-for="stratagem in stratagemData.subsections[subsection].stratagems" :key="stratagem.name">
            {{ stratagem.name }}
            {{ stratagem.image_path }}
            <img src="{{ stratagem.image_path }}" alt="image">
          </li>
        </ul>
      </li>
    </ul>
  </div>
</template>

<style scoped>

</style>