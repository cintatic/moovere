<template>
  <div>
    <div
      class="px-4 py-5 w-full fixed shadow bg-white z-30 backdrop-filter backdrop-blur-xl bg-opacity-60"
    >
      <div class="relative flex items-center text-center justify-between">
        <div class="w-1/2 md:w-48 md:ml-10">
          <NuxtLink to="/" aria-label="Moovere" title="Moovere">
            <nuxt-img class="w-full" src="/svg/logo-title.svg" />
          </NuxtLink>
        </div>
        <ul class="flex items-center hidden space-x-8 lg:flex mr-6">
          <li>
            <NuxtLink
              to="/quienes-somos"
              aria-label="Quienes somos"
              title="Quienes somos"
              class="font-medium tracking-wide text-purple transition-colors duration-200 hover:text-deep-purple-accent-400"
              >¿Quiénes somos?</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/equipos"
              aria-label="Equipos"
              title="Equipos"
              class="font-medium tracking-wide text-purple transition-colors duration-200 hover:text-deep-purple-accent-400"
              >Equipos</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/servicios"
              aria-label="Servicios"
              title="Servicios"
              class="font-medium tracking-wide text-purple transition-colors duration-200"
              >Servicios</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/asesoria"
              aria-label="Asesoria"
              title="Asesoria"
              class="font-medium tracking-wide text-purple transition-colors duration-200"
              >Asesoría</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/galeria"
              aria-label="galeria"
              title="galeria"
              class="font-medium tracking-wide text-purple transition-colors duration-200"
              >Galería</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/blog"
              aria-label="blog"
              title="blog"
              class="font-medium tracking-wide text-purple transition-colors duration-200"
              >Blog</NuxtLink
            >
          </li>
          <li>
            <NuxtLink
              to="/contacto"
              aria-label="Contacto"
              title="Contacto"
              class="font-medium tracking-wide text-purple transition-colors duration-200"
              >Contáctanos</NuxtLink
            >
          </li>
        </ul>
        <div class="lg:hidden">
          <button
            aria-label="Open Menu"
            title="Open Menu"
            class="p-2 -mr-1 transition duration-200 rounded focus:outline-none focus:shadow-outline"
            @click="isMenuOpen = true"
          >
            <svg class="w-5 text-purple" viewBox="0 0 24 24">
              <path
                fill="currentColor"
                d="M23,13H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,13,23,13z"
              ></path>
              <path
                fill="currentColor"
                d="M23,6H1C0.4,6,0,5.6,0,5s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,6,23,6z"
              ></path>
              <path
                fill="currentColor"
                d="M23,20H1c-0.6,0-1-0.4-1-1s0.4-1,1-1h22c0.6,0,1,0.4,1,1S23.6,20,23,20z"
              ></path>
            </svg>
          </button>
          <div v-if="isMenuOpen" class="absolute top-0 left-0 w-full">
            <div class="p-5 bg-gray-100 border rounded shadow-sm">
              <div class="flex items-center justify-between mb-4">
                <div class="mx-auto">
                  <a
                    href="/"
                    aria-label="Company"
                    title="Company"
                    class="inline-flex items-center"
                  >
                    <nuxt-img class="h-8" src="/svg/logo-title.svg" />
                  </a>
                </div>
                <div>
                  <button
                    aria-label="Close Menu"
                    title="Close Menu"
                    class="p-2 -mt-2 -mr-2 transition duration-200 rounded hover:bg-gray-200 focus:bg-gray-200 focus:outline-none focus:shadow-outline"
                    @click="isMenuOpen = false"
                  >
                    <svg class="w-5 text-purple" viewBox="0 0 24 24">
                      <path
                        fill="currentColor"
                        d="M19.7,4.3c-0.4-0.4-1-0.4-1.4,0L12,10.6L5.7,4.3c-0.4-0.4-1-0.4-1.4,0s-0.4,1,0,1.4l6.3,6.3l-6.3,6.3 c-0.4,0.4-0.4,1,0,1.4C4.5,19.9,4.7,20,5,20s0.5-0.1,0.7-0.3l6.3-6.3l6.3,6.3c0.2,0.2,0.5,0.3,0.7,0.3s0.5-0.1,0.7-0.3 c0.4-0.4,0.4-1,0-1.4L13.4,12l6.3-6.3C20.1,5.3,20.1,4.7,19.7,4.3z"
                      ></path>
                    </svg>
                  </button>
                </div>
              </div>
              <nav>
                <ul class="space-y-4">
                  <li>
                    <NuxtLink
                      to="/quienes-somos"
                      aria-label="Quienes somos"
                      title="Quienes somos"
                      class="font-medium tracking-wide text-purple transition-colors duration-200 hover:text-deep-purple-accent-400"
                      >¿Quiénes somos?</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/equipos"
                      aria-label="Equipos"
                      title="Equipos"
                      class="font-medium tracking-wide text-purple transition-colors duration-200 hover:text-deep-purple-accent-400"
                      >Equipos</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/servicios"
                      aria-label="Servicios"
                      title="Servicios"
                      class="font-medium tracking-wide text-purple transition-colors duration-200"
                      >Servicios</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/asesoria"
                      aria-label="Asesoria"
                      title="Asesoria"
                      class="font-medium tracking-wide text-purple transition-colors duration-200"
                      >Asesoría</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/galeria"
                      aria-label="galeria"
                      title="galeria"
                      class="font-medium tracking-wide text-purple transition-colors duration-200"
                      >Galería</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/blog"
                      aria-label="blog"
                      title="blog"
                      class="font-medium tracking-wide text-purple transition-colors duration-200"
                      >Blog</NuxtLink
                    >
                  </li>
                  <li>
                    <NuxtLink
                      to="/contacto"
                      aria-label="Contacto"
                      title="Contacto"
                      class="font-medium tracking-wide text-purple transition-colors duration-200 hover:text-deep-purple-accent-400"
                      >Contáctanos</NuxtLink
                    >
                  </li>
                </ul>
                <ul class="flex mt-4 justify-center space-x-4">
                  <li>
                    <!--
                    <a href="tel:5628348062" class="text-mint mx-5">
                      <svg
                        fill="currentColor"
                        class="h-6 w-6"
                        viewBox="0 0 512 512"
                      >
                        <path
                          d="M511.2 387l-23.25 100.8c-3.266 14.25-15.79 24.22-30.46 24.22C205.2 512 0 306.8 0 54.5c0-14.66 9.969-27.2 24.22-30.45l100.8-23.25C139.7-2.602 154.7 5.018 160.8 18.92l46.52 108.5c5.438 12.78 1.77 27.67-8.98 36.45L144.5 207.1c33.98 69.22 90.26 125.5 159.5 159.5l44.08-53.8c8.688-10.78 23.69-14.51 36.47-8.975l108.5 46.51C506.1 357.2 514.6 372.4 511.2 387z"
                        />
                      </svg>
                    </a>
                    -->
                    <a href="tel:5628348062">
                      <font-awesome-icon
                        class="text-2xl mx-5 text-mint"
                        :icon="['fas', 'phone']"
                      />
                    </a>
                    <a
                      href="https://api.whatsapp.com/send?phone=528134421227&text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20agendar%20una%20cita.%20"
                    >
                      <font-awesome-icon
                        class="text-3xl mx-5 text-mint"
                        :icon="['fab', 'whatsapp']"
                      />
                    </a>

                    <a href="https://goo.gl/maps/5RkadQJig6YjeLBt5">
                      <font-awesome-icon
                        class="text-3xl mx-5 text-mint"
                        :icon="['fas', 'map-marked-alt']"
                      />
                    </a>
                  </li>
                </ul>
              </nav>
            </div>
          </div>
        </div>
        <!--
      <ul class="flex items-center hidden space-x-8 lg:flex">
        <li>
          <a href="tel:5628348062">
            <font-awesome-icon
              class="text-2xl mx-5 text-mint"
              :icon="['fas', 'phone']"
            />
          </a>
          <a href="tel:5628348062">
            <font-awesome-icon
              class="text-3xl mx-5 text-mint"
              :icon="['fab', 'whatsapp']"
            />
          </a>
        </li>
      </ul>
      <ul class="lg:hidden space-x-6">
        <a href="tel:5628348062">
          <font-awesome-icon
            class="text-2xl text-mint"
            :icon="['fas', 'phone']"
          />
        </a>
        <a href="tel:5628348062">
          <font-awesome-icon
            class="text-3xl text-mint"
            :icon="['fab', 'whatsapp']"
          />
        </a>
      </ul>
      --></div>
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      isMenuOpen: false,
    };
  },
};
</script>
