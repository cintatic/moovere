<template>
  <div>
    <NavProd />
    <section class="text-gray-900 body-font">
      <div
        class="container mx-auto flex px-5 py-24 items-center justify-center flex-col"
      >
        <nuxt-img
          class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded"
          alt="hero"
          src="/img/equipos/KSYIO.png"
        />
        <div class="text-justify lg:w-2/3 w-full">
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-purple"
          >
            Kysio
          </h1>
          <br />
          <p class="mb-8 leading-relaxed">
            Kysio te permite realizar trabajos de resistencia progresivos,
            programados y controlado gracias a su sensor y sistema de
            biofeedback. Artículo ofrece la posibilidad de realizar la
            recuperación articular y muscular fortalecer el trabajo de forma
            independiente, cuantificada y reproducible para todo el cuerpo.
          </p>
          <div
            class="px-4 py-16 mx-auto sm:max-w-xl md:max-w-full lg:max-w-screen-xl md:px-24 lg:px-8 lg:py-20"
          >
            <div
              class="grid grid-cols-2 gap-5 row-gap-5 sm:grid-cols-3 lg:grid-cols-6"
            >
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'heartbeat']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Prevención
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'check-square']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Completo
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'fist-raised']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Resistencia
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'universal-access']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Recuperación
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'dumbbell']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Fuerza
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'running']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Coordinación muscular
                </h6>
              </div>
            </div>
          </div>
          <div class="flex justify-center">
            <a
              href="https://api.whatsapp.com/send?phone=528134421227&text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20agendar%20una%20cita.%20"
              class="inline-flex text-white bg-purple border-0 py-2 px-6 focus:outline-none hover:bg-mint rounded text-lg"
            >
              Agenda una cita
            </a>
            <NuxtLink
              to="/equipos"
              class="ml-4 inline-flex text-gray-700 bg-gray-100 border-0 py-2 px-6 focus:outline-none hover:bg-gray-200 rounded text-lg"
            >
              Equipos
            </NuxtLink>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>
