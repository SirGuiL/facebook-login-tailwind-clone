<script setup>
const props = defineProps({
  type: {
    type: String,
    default: "text",
  },
});
</script>

<template>
  <input
    type="text"
    name=""
    id=""
    placeholder="E-mail ou telefone"
    class="text-input"
    v-if="type == 'text'"
  />
  <input
    type="password"
    name=""
    id=""
    placeholder="Senha"
    class="pass-input"
    v-else
  />
</template>

<style scoped></style>
