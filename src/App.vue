<script setup lang="ts">
import { ref } from 'vue';

import ButtonVue from './components/Button.vue';

const count = ref(0);

const updateCounter = () => {
  count.value++
}
</script>

<template>
  <ButtonVue :text="count" class="bg-[#5a5fda]" @click="updateCounter"/>
</template>

<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  text-align: center;
  color: #2c3e50;
  margin-top: 60px;
}
</style>
