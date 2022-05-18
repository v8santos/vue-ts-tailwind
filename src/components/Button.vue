<script setup lang="ts">
defineProps<{
  text: string | number,
  color?: string
}>()


</script>

<template>
  <button class="rounded-sm px-2 leading-7 focus:ring-1 focus:ring-[#e1a5d2] outline-none">
    {{ text }}
  </button>
</template>
