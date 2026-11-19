<template>
  <section class="px-6 micro:px-18 py-30 flex justify-center">
    <div class="max-w-300 w-full flex-col space-y-10">
      <SectionsTitle>Serviços</SectionsTitle>
      <div class="grid grid-cols-1 md:grid-cols-2 xl:grid-cols-4  gap-16 xl:gap-8">
        <ServicesCard>
          <template #title>Assentamento de azulejos</template>
          <template #description>Paredes de cozinhas, banheiros e áreas de serviço com prumo e nível perfeitos.</template>
        </ServicesCard>
        <ServicesCard>
          <template #title>Porcelanato e pisos</template>
          <template #description>Peças de grande formato, retificadas e com junta mínima, sem desnível</template>
        </ServicesCard>
        <ServicesCard>
          <template #title>Revestimentos especiais</template>
          <template #description>Pastilhas, mosaicos, 3D e pedras naturais com acabamento fino.</template>
        </ServicesCard>
        <ServicesCard>
          <template #title>Reformas e reparos</template>
          <template #description>Fazemos demolição impermeabilização contra piso, Alvenaria, Reboco e Hidráulica.</template>
        </ServicesCard>
      </div>
    </div>
  </section>
</template>

<script setup>
  import SectionsTitle from './SectionsTitle.vue';
  import ServicesCard from './ServicesCard.vue';
</script>
