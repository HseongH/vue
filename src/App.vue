<script setup>
import { ref } from 'vue';
import ChildComp from './ChildComp.vue';

const msg = ref('Vue는 개발자에게 정말 유용하죠! 🎁');
</script>

<template>
  <ChildComp>{{ msg }}</ChildComp>
</template>
