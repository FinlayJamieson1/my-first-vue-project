<script setup>
import { useStorage } from '@/composables/useStorage.js'

let food = useStorage('food');
let age = useStorage('age');

</script>

<template>
  <main>
    <p>What is your favourite food? <input type="text" v-model="food" /></p>
    <p>How old are you? <input type="text" v-model="age"></p>
  </main>
</template>

<!--<script setup>-->
<!--import {useFlash} from '@/composables/useFlash.js'-->

<!--let { flash } = useFlash();-->

<!--</script>-->

<!--<template>-->
<!--  <main>-->
<!--    <p>-->
<!--      <button @click="flash('Yay!', 'It Works!', 'success')">Click Me</button>-->
<!--    </p>-->
<!--  </main>-->
<!--</template>-->

<!--<script setup>-->
<!--import TheWelcome from '../components/TheWelcome.vue'-->
<!--import { ref } from "vue";-->

<!--let message = ref("Hello World!");-->

<!--let doSomething = () => {-->
<!--  alert("doing it now");-->
<!--};-->

<!--setTimeout(() => {-->
<!--  message.value = "I have been changed!";-->
<!--}, 2000);-->

<!--</script>-->

<!--<template>-->
<!--  <main>-->
<!--    <TheWelcome />-->
<!--    <p>{{ message }}</p>-->
<!--    <button @click="doSomething">Click Me</button>-->
<!--  </main>-->
<!--</template>-->
