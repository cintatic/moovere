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
          src="/img/equipos/INSHAPE.png"
        />
        <div class="text-justify lg:w-2/3 w-full">
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-purple"
          >
            INSHAPE
          </h1>
          <br />
          <p class="mb-8 leading-relaxed">
            <strong class="text-purple">Tratamiento electromagnético</strong>
            <br />consiste en utilizar los potentes impulsos eléctricos
            generados por el campo electromagnético. Esta tecnología es para
            estimular el músculo e inducir el metabolismo del cuerpo.
            <br />
            <br />En el pasado, tradicionalmente se ha utilizado más para la
            rehabilitación muscular y liberación de dolor muscular con el
            propósito de terapia física. Hoy en día, ha sido adoptado y
            transformado para usos médico-estéticos, especialmente con el
            propósito de realizar la conformación corporal no invasiva.
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
                    :icon="['fas', 'check-square']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Resultados
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'ban']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  No invasivo
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'spa']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Bienestar
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'clock']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  30 min
                </h6>
              </div>
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
                  Salud
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'gem']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Belleza
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
