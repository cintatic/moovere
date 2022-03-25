<template>
  <div>
    <NavProd />
    <section class="text-gray-900 body-font">
      <div
        class="container mx-auto flex px-5 py-24 items-center justify-center flex-col"
      >
        <nuxt-img
          class="lg:w-2/6 md:w-3/6 w-5/6 mb-10 object-cover object-center rounded"
          alt="imagen_icoone"
          src="/img/equipos/ICOONE.PNG"
        />
        <div class="text-justify lg:w-2/3 w-full">
          <h1
            class="title-font sm:text-4xl text-3xl mb-4 font-medium text-purple"
          >
            ICOONE
          </h1>
          <br />
          <p class="mb-8 leading-relaxed">
            <strong class="text-purple">La ciencia de la piel</strong>
            <br />
            La ciencia es la base del desarrollo tecnológico de todos nuestros
            dispositivos, fruto de la investigación continua en la
            identificación de soluciones innovadoras para mejorar la calidad de
            vida de nuestros clientes.
            <br />
            <br />
            A través de la microestimulación, la innovadora tecnología icoone
            ofrece un tratamiento personalizado y eficaz de la piel del rostro y
            del cuerpo, al mismo tiempo que drena, reafirma y remodela la
            silueta. La gama de productos icoone para aplicaciones estéticas
            está disponible en dos versiones, con o sin LÁSER y LED.
            <br />
            <br /><strong class="text-purple">celulitis</strong> <br />
            Este tratamiento dirigido reduce visiblemente la aparición de piel
            de naranja antiestética. icoone ayuda a suavizar la piel, mejorando
            el drenaje y la circulación sanguínea, y restaurando una forma
            corporal armoniosa.
            <br />
            <br /><strong class="text-purple">Moldea el cuerpo</strong> <br />
            Diseñado para trabajar en los depósitos de grasa adiposos rebeldes,
            este tratamiento de contorno corporal le da a toda la figura una
            nueva armonía, así como una agradable sensación de ligereza y
            bienestar.
            <br />
            <br /><strong class="text-purple"
              >Relajación y rejuvenecimiento.</strong
            >
            <br />
            Icoone consigue la relajación total de los tejidos, favoreciendo la
            liberación de endorfinas y dando como resultado una sensación
            general de bienestar.
            <br />
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
                    :icon="['fas', 'file-medical']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Médico
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'sort-down']"
                    class="text-purple text-3xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Reduce
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fas', 'hands']"
                    class="text-purple text-2xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Moldea
                </h6>
              </div>
              <div class="text-center">
                <div
                  class="flex items-center justify-center w-10 h-10 mx-auto mb-4 rounded-full bg-indigo-50 sm:w-12 sm:h-12"
                >
                  <font-awesome-icon
                    :icon="['fa', 'sort-up']"
                    class="text-purple text-3xl"
                  />
                </div>
                <h6
                  class="mb-2 text-sm font-bold leading-5 tracking-wider uppercase"
                >
                  Mejora
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
