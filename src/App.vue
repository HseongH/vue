<script setup>
import { onMounted, ref } from 'vue';

const p = ref(null);

onMounted(() => {
  p.value.textContent = 'On Mounted!!';
});
</script>

<template>
  <p ref="p">안녕</p>
</template>
