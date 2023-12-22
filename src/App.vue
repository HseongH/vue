<script setup>
import { ref } from 'vue';

const text = ref('');

const onInput = (event) => (text.value = event.target.value);
</script>

<template>
  <input :value="text" @input="onInput" placeholder="여기에 입력하기" />
  <p>{{ text }}</p>
</template>
