<script setup>
const props = defineProps({
  link: {
    type: String,
    default: "text",
  },
});
</script>

<template>
  <li class="mr-3">
    <a href="#" class="hover:underline">{{ link }}</a>
  </li>
</template>

<style scoped></style>
