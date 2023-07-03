<script setup lang="ts">
import { ref } from 'vue'

defineProps<{ msg: string }>()

const form = ref({})
</script>

<template>
  <form :data="[1,2,3]" :model="{a: '1'}"></form>
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
