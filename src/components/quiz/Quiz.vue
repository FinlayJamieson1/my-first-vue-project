<script setup>
import QuizHeader from '@/components/quiz/QuizHeader.vue';
import QuizQuestion from '@/components/quiz/QuizQuestion.vue';
import QuizFooter from '@/components/quiz/QuizFooter.vue';
import {state} from '@/stores/quizStore.js'

</script>

<template>
  <QuizHeader />
  <QuizQuestion />
  <QuizFooter />
</template>
