<script setup>
import List from '../molecules/List.vue'
</script>

<template>
  <footer>
    <div class="lg:w-980px mx-auto py-8 text-center lg:text-current">
      <div>
        <ul class="grid grid-cols-2 lg:flex text-gray-600 text-xs lg:text-sm">
          <li class="mr-3">
            <a href="#" class="hover:underline">Português (Brazil)</a>
          </li>
          <li class="mr-3">
            <a href="#" class="hover:underline">English (US)</a>
          </li>
          <li class="mr-3">
            <a href="#" class="hover:underline">Español</a>
          </li>
          <li class="mr-3">
            <a href="#" class="hover:underline">Français (France)</a>
          </li>
          <li class="mr-3">
            <a href="#" class="hover:underline">Italiano</a>
          </li>
        </ul>
      </div>
      <div class="hidden lg:block border-t border-gray-400 pt-3 mt-3"></div>
      <div>
        <List />
      </div>
      <div class="pt-4 text-xs text-gray-600 text-center lg:text-left">
        <p>Facebook &copy; 2020</p>
      </div>
    </div>
  </footer>
</template>

<style scoped>
</style>
