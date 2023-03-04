<script setup>
import CardForm from '../molecules/CardForm.vue'
</script>

<template>
  <main>
    <div class="lg:bg-main-gray lg:pt-30 lg:pb-40">
      <div class="grid grid-cols-1 lg:grid-cols-2 lg:w-980px mx-auto">
        <div class="pt-10">
          <img src="../../assets/logo_facebook.svg" alt="" class="w-30 mx-auto lg:mx-0 lg:w-290px lg:-mb-4 lg:-ml-8">
          <p class="hidden lg:flex text-subtitle leading-8 w-500px pr-6">O Facebook ajuda você a se conectar e compartilhar com as pessoas que fazem parte da sua vida.</p>
        </div>
        <CardForm />
      </div>
    </div>
  </main>
</template>

<style scoped>
</style>
