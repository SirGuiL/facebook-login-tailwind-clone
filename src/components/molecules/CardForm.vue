<script setup>
import Input from '../atoms/Input.vue'
import PrimaryButton from '../atoms/PrimaryButton.vue';
import SignInButton from '../atoms/SignInButton.vue';
import BottomPhrase from '../atoms/BottomPhrase.vue';
</script>

<template>
    <div class="lg:w-396px lg:place-self-end">
      <div class="p-4 lg:border lg:shadow-xl rounded-lg bg-white">
        <form action="" class="flex flex-col">
          <Input />
          <Input type="pass" />
          
          <PrimaryButton />
        </form>
        <div
          class="flex flex-col divide-y divide-gray-400 text-center mt-2 lg:mt-0"
        >
          <div class="pb-4 order-2 lg:order-1">
            <a href="#" class="text-blue-600 hover:underline"
              >Esqueceu a senha?</a
            >
          </div>
          <div class="pb-6 pt-8 order-1 lg:order-2">
            <SignInButton />
          </div>
        </div>
      </div>
      <div class="hidden lg:block text-sm mt-5 text-center">
        <BottomPhrase />
      </div>
    </div>
</template>

<style scoped></style>
