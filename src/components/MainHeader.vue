<template>
  <header class="flex justify-center">
    <div class="flex justify-between items-center sm:max-w-140 md:max-w-180 lg:max-w-240 xl:max-w-300 w-full">
      <figure>
        <img class="w-40 bg-white" src="/src/img/logo.png" alt="">
      </figure>
      <a :href="whatsappUrl" target="_blank" class="hidden sm:block px-4 py-2 rounded-lg font-bold bg-gray-900 text-gold-default h-fit">Pedir orçamento</a>
    </div>
  </header>
</template>

<script setup>
const telefone = '5511995076579'
const mensagem = 'Olá! Gostaria de solicitar um orçamento.'

const whatsappUrl = `https://wa.me/${telefone}?text=${encodeURIComponent(mensagem)}`
</script>
