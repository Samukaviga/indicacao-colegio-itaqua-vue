<template>
  <section class="w-full lg:w-1/2 flex flex-col items-center justify-center">
    <div class="w-full flex justify-center mb-6 pt-8">
      <img :src="logoBolsas" alt="Bolsas de Estudo Colégio Itaquá"
           class="max-w-xs md:max-w-sm lg:max-w-md w-full mb-4 drop-shadow-lg select-none pointer-events-none"
           draggable="false" />
    </div>
    <div class="w-full flex justify-center mt-3 mb-4 pb-6">
      <img :src="logo" alt="Colégio Itaquá" class="h-20 lg:h-25" fetchpriority="high" />
    </div>
  </section>
</template>

<script setup>
import logo from '@/assets/images/logo.webp'
import logoBolsas from '@/assets/images/roleta-2.webp'
</script>
