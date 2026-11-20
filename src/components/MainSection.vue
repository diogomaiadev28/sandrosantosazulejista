<template>
  <main class="bg-[#1e2225] py-16 sm:py-20 px-8 micro:px-16 w-full flex justify-center">
    <div class="max-w-300 flex-col lg:flex-row flex justify-between items-center space-x-0 lg:space-x-20 space-y-10 lg:space-y-0">
      <div class="sm:w-140 md:w-160 lg:w-200 space-y-6 grow">
        <h5 class="text-gold-default tracking-widest font-bold font-mono">AZULEJISTA PROFISSIONAL</h5>
        <h1 class="text-3xl sm:text-4xl md:text-5xl font-black text-white leading-10 sm:leading-12 md:leading-16">Acabamento impecável, <span class="text-gold-default">peça por peça.</span></h1>
        <p class="text-white text-lg">Mais de 18 anos assentando azulejos, porcelanatos e revestimentos em São Paulo. Pontualidade, limpeza e capricho em cada obra.</p>
        <div class="flex md:flex-row flex-col space-y-4 md:space-y-0 md:space-x-4">
          <figure class="md:hidden block">
            <img class="w-140 xl:w-200 border-gold-default border-3 rounded-xl" src="/src/img/Untitled.jpg" alt="">
          </figure>
          <WhatsappButton>Chamar no WhatsApp</WhatsappButton>
          <a href="#callme" class="bg-[#1e2225] border-2 border-gold-default text-gold-default text-lg micro:text-xl font-semibold rounded-lg px-5 py-3">Ver Contato</a>
        </div>
      </div>
      <figure class="hidden md:block">
        <img class="w-140 xl:w-200 border-gold-default border-3 rounded-xl" src="/src/img/Untitled.jpg" alt="">
      </figure>
    </div>
  </main>
</template>

<script setup>
  import WhatsappButton from './WhatsappButton.vue';
</script>
