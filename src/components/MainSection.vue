<template>
  <main class="bg-[#1e2225] py-20 px-16 w-full flex justify-center">
    <div class="max-w-300 flex justify-between items-center space-x-20">
      <div class="w-200 space-y-4 grow">
        <h5 class="text-gold-default tracking-widest font-bold font-mono">AZULEJISTA PROFISSIONAL</h5>
        <h1 class="text-5xl font-black text-white leading-16">Acabamento impecável, <span class="text-gold-default">peça por peça.</span></h1>
        <p class="text-white text-lg">Mais de 15 anos assentando azulejos, porcelanatos e revestimentos em São Paulo. Pontualidade, limpeza e capricho em cada obra.</p>
        <div class="flex space-x-4">
          <WhatsappButton>Chamar no WhatsApp</WhatsappButton>
          <button class="bg-[#1e2225] border-2 border-gold-default text-gold-default text-xl font-semibold rounded-lg px-5 py-3">Ver Contato</button>
        </div>
      </div>
      <figure>
        <img class="w-200 border-gold-default border-3 rounded-xl" src="/src/img/example1.jpg" alt="">
      </figure>
    </div>
  </main>
</template>

<script setup>
  import WhatsappButton from './WhatsappButton.vue';
</script>
