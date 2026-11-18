<template>
  <main class="bg-[#1e2225] py-20 px-16 w-full flex justify-center">
    <div class="max-w-300 flex justify-between items-center space-x-20">
      <div class="w-200 space-y-12 grow">
        <div class="flex flex-col space-y-2">
          <h2 class="text-white text-4xl font-black">Fale comigo</h2>
          <div class="w-16 bg-gold-default h-1"></div>
        </div>
        <div class="flex flex-col space-y-3">
          <CallInfo>
            <template #title>Whatsapp / Telefone</template>
            <template #description>(11) 99507-6579</template>
          </CallInfo>
          <CallInfo>
            <template #title>E-mail</template>
            <template #description>sandro.ts.santana@gmail.com</template>
          </CallInfo>
          <CallInfo>
            <template #title>Atendimento</template>
            <template #description>São Paulo</template>
          </CallInfo>
          <CallInfo>
            <template #title>Horário</template>
            <template #description>Segunda a sábado, das 7h às 18h</template>
          </CallInfo>
        </div>
        <WhatsappButton>Solicitar orçamento grátis</WhatsappButton>
      </div>
      <figure>
        <img class="w-200 border-gold-default border-3 rounded-xl" src="/src/img/example1.jpg" alt="">
      </figure>
    </div>
  </main>
</template>

<script setup>
  import CallInfo from './CallInfo.vue';
  import WhatsappButton from './WhatsappButton.vue';
</script>
