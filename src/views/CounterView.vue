<script setup>
import { useCounterStore } from '@/stores/counterStore.js'

let counter = useCounterStore();
</script>
<template>
  <main>
    <h1>{{ counter.count }}</h1>

    <button
      @click="counter.increment" :disabled="! counter.remaining">
      Increment ({{counter.remaining}}) Remaining
    </button>
  </main>
</template>
