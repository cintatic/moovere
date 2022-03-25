<template>
  <div>
    <transition name="home"> </transition>

    <div
      class="flex flex-col h-screen items-center justify-center bg-sm-background md:bg-lg-background bg-cover"
    >
      <MoovereLogo />
      <!-- BOTON FLECHA 
      <div class="flex w-full">
        <div v-scroll-to="'#quienes'" class="mx-auto">
          <font-awesome-icon
            class="animated bounce infinite text-purple text-2xl"
            :icon="['fas', 'arrow-down']"
          />
        </div>
      </div>-->
    </div>

    <!-- QUIENES SOMOS -->

    <!-- SECCION DE PRODUCTOS -->
  </div>
</template>

<script>
export default {}
</script>

<style>
.home-enter-active,
.home-leave-active {
  animation: slideInDown 0.5s;
}
.home-enter,
.home-leave-active {
  animation: slideInUp 0.5s;
}
</style>
