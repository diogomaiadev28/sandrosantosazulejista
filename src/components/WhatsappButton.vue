<template>
  <a :href="whatsappUrl" target="_blank" class="bg-gold-default rounded-lg micro:text-xl text-lg font-semibold text-[#1e2225] px-4 py-3"><slot></slot></a>
</template>

<script setup>
const telefone = '5511995076579'
const mensagem = 'Olá! Gostaria de solicitar um orçamento.'

const whatsappUrl = `https://wa.me/${telefone}?text=${encodeURIComponent(mensagem)}`
</script>
