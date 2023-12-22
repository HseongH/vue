<script setup>
import { reactive, ref } from 'vue';

const message = ref('Title');
const counter = reactive({ count: 0 });

const increament = () => counter.count++;
</script>

<template>
  <h1>{{ message }}</h1>
  <button @click="increament">{{ counter.count }}번 클릭</button>
</template>
