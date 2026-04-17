
<template>
  <NButton>Click me</NButton>
  <NSelect v-model="value" :options="options">
  </NSelect>

</template>

<script setup lang="ts">
import { ref } from 'vue'
import {NButton,NSelect} from 'naive-ui'


const value = ref('')
const options = ref([
  {label: 'Option 1', value: '1'},
  {label: 'Option 2', value: '2'},
  {label: 'Option 3', value: '3'},
])
</script>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
