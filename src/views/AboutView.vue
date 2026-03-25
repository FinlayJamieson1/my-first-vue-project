<script setup>
import { useFlash } from '@/composables/useFlash.js'

let { flash } = useFlash()
</script>
<template>
  <main>
    <p>
      <button @click="flash('Abouting', 'It Works!', 'info')">Click Me</button>
    </p>
  </main>
</template>
