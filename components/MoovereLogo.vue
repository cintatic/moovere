<template>
  <div class="w-4/5 md:w-1/2 md:mt-48 mt-20">
    <nuxt-img class="w-full" src="svg/logo.svg" />
    <div class="mt-12">
      <p class="mb-8 leading-relaxed text-center text-purple text-xl font-bold">
        Somos un centro de rehabilitación, acondicionamiento físico y estético.
        Trabajamos con equipos de última generación con tecnología desarrollada
        en Francia, Italia y Alemania.
      </p>
      <div class="flex">
        <NuxtLink
          to="/quienes-somos"
          class="mx-auto inline-flex text-gray-50 bg-purple border-0 py-2 px-6 focus:outline-none hover:bg-amber-700 rounded text-lg"
        >
          Lee más
        </NuxtLink>
      </div>
    </div>
  </div>
</template>

<script>
export default {}
</script>
