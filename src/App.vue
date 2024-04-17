<script setup>
import SearchInput from './components/SearchInput.vue'

SearchInput
</script>

<template>
  <!-- Date -->
  <div class="text-center mb-6">
    {{
      new Date().toLocaleDateString('en-us', {
        weekday: 'long',
        year: 'numeric',
        month: 'long',
        day: 'numeric'
      })
    }}
  </div>

  <!-- Search -->
  <div><SearchInput /></div>
</template>
