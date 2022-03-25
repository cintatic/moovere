<template>
  <div>
    <section
      id="quienes"
      data-aos="fade-in"
      data-aos-duration="2000"
      class="text-gray-900 body-font"
    >
      <div
        class="container mx-auto flex px-5 pt-24 pb-12 md:flex-row flex-col items-center"
      >
        <div class="lg:max-w-lg lg:w-full md:w-1/2 mx-auto w-5/6 mb-10 md:mb-0">
          <nuxt-img
            class="border-purple border-8 object-cover object-center rounded-full border-opacity-40"
            alt="hero"
            src="/img/moovere-quienes.jpeg"
          />
        </div>

        <div
          class="lg:flex-grow md:w-1/2 lg:pl-24 md:pl-16 flex flex-col md:items-start md:text-left items-center text-center"
        >
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-purple"
          >
            ¿Quiénes somos?
          </h1>
          <p class="mb-8 leading-relaxed text-gray-900">
            Somos un centro de rehabilitación, acondicionamiento físico y
            estético. Trabajamos con equipos de última generación con tecnología
            desarrollada en Francia, Italia y Alemania.
            <br />
            <br />Los más importantes llamados:
            <strong class="text-purple">
              Imoove, Icoone, Inshape, Kysio y Vacumed.</strong
            >
          </p>
        </div>
      </div>
    </section>

    <div
      class="px-4 mx-auto pb-12 sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8"
    >
      <div class="grid gap-5 row-gap-5 sm:grid-cols-2 lg:grid-cols-4">
        <div class="px-12 text-center sm:px-0">
          <div
            class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
          >
            <font-awesome-icon
              :icon="['fas', 'hand-sparkles']"
              class="text-purple text-2xl"
            />
          </div>
          <h6 class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase">
            Transparencia
          </h6>
        </div>
        <div class="px-12 text-center sm:px-0">
          <div
            class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
          >
            <font-awesome-icon
              :icon="['fas', 'hands-helping']"
              class="text-purple text-2xl"
            />
          </div>
          <h6 class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase">
            Honestidad
          </h6>
        </div>
        <div class="px-12 text-center sm:px-0">
          <div
            class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
          >
            <font-awesome-icon
              :icon="['fas', 'universal-access']"
              class="text-purple text-2xl"
            />
          </div>
          <h6 class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase">
            Libertad
          </h6>
        </div>
        <div class="px-12 text-center sm:px-0">
          <div
            class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
          >
            <font-awesome-icon
              :icon="['fas', 'check-square']"
              class="text-purple text-2xl"
            />
          </div>
          <h6 class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase">
            Excelencia
          </h6>
        </div>
      </div>
    </div>
  </div>
</template>
