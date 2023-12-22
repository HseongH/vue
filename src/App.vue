<script setup>
import { ref } from 'vue';

const awesome = ref(true);

const toggle = () => (awesome.value = !awesome.value);
</script>

<template>
  <button @click="toggle">토글 버튼</button>
  <h1 v-if="awesome">Vue는 굉장해! 엄청나!</h1>
  <h1 v-else="awesome">오 안돼 😢</h1>
</template>
