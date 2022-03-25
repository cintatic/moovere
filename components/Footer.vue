<template>
  <div
    id="contacto"
    class="
      px-4
      pt-16
      mx-auto
      sm:max-w-xl
      md:max-w-full
      lg:max-w-screen-xl
      md:px-24
      lg:px-8
    "
  >
    <div class="grid gap-10 row-gap-6 mb-8 sm:grid-cols-2 lg:grid-cols-4">
      <div class="sm:col-span-2">
        <div class="w-1/2 md:w-48">
          <a href="/" aria-label="Company" title="Company">
            <nuxt-img class="w-full" src="/movere-full.png" />
          </a>
        </div>
        <div class="mt-6 lg:max-w-sm">
          <p class="text-sm text-gray-800">
            Contáctanos para conocer más de los equipos o las sesiones que
            Moovere tiene para ti. <br />
            Agenda tu cita por WhatsApp o llamanos, estamos para atenderte.
          </p>
        </div>
      </div>
      <div class="space-y-2 text-sm">
        <p class="text-base font-bold tracking-wide text-purple">CONTACTO</p>
        <div class="flex">
          <p class="mr-1 text-gray-800">Teléfono:</p>
          <a
            href="tel:81-2235-9751"
            aria-label="Our phone"
            title="Teléfono"
            class="transition-colors duration-300 text-purple hover:text-mint"
            >81-2235-9751</a
          >
        </div>
        <div class="flex">
          <p class="mr-1 text-gray-800">WhatsApp:</p>
          <a
            href="https://api.whatsapp.com/send?phone=528134421227&text=%C2%A1Hola!%20Me%20gustar%C3%ADa%20agendar%20una%20cita.%20"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Our whatsapp"
            title="Whatsapp"
            class="transition-colors duration-300 text-purple hover:text-mint"
            >81-3442-1227
          </a>
        </div>
        <div class="flex">
          <p class="mr-1 text-gray-800">Email:</p>
          <a
            href="mailto:movereclinic@gmail.com"
            aria-label="Our email"
            title="Email"
            class="transition-colors duration-300 text-purple hover:text-mint"
            >movereclinic@gmail.com</a
          >
        </div>
        <div class="flex">
          <p class="mr-1 text-gray-800">Dirección:</p>
          <a
            href="https://goo.gl/maps/5RkadQJig6YjeLBt5"
            target="_blank"
            rel="noopener noreferrer"
            aria-label="Our address"
            title="Dirección"
            class="transition-colors duration-300 text-purple hover:text-mint"
          >
            Río Guadalquivir #237, segundo piso. Del Valle, Monterrey, N.L.
          </a>
        </div>
      </div>
      <div>
        <span class="text-base font-bold tracking-wide text-gray-900"
          >SÍGUENOS EN REDES</span
        >
        <div class="flex items-center mt-1 space-x-3">
          <a
            href="https://instagram.com/mxmoovere?utm_medium=copy_link"
            class="text-purple transition-colors duration-300 hover:text-mint"
          >
            <svg viewBox="0 0 30 30" fill="currentColor" class="h-6">
              <circle cx="15" cy="15" r="4"></circle>
              <path
                d="M19.999,3h-10C6.14,3,3,6.141,3,10.001v10C3,23.86,6.141,27,10.001,27h10C23.86,27,27,23.859,27,19.999v-10   C27,6.14,23.859,3,19.999,3z M15,21c-3.309,0-6-2.691-6-6s2.691-6,6-6s6,2.691,6,6S18.309,21,15,21z M22,9c-0.552,0-1-0.448-1-1   c0-0.552,0.448-1,1-1s1,0.448,1,1C23,8.552,22.552,9,22,9z"
              ></path>
            </svg>
          </a>
          <a
            v-if="ios"
            href="fb://profile/215022017197560/"
            class="text-purple transition-colors duration-300 hover:text-mint"
          >
            <svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
              <path
                d="M22,0H2C0.895,0,0,0.895,0,2v20c0,1.105,0.895,2,2,2h11v-9h-3v-4h3V8.413c0-3.1,1.893-4.788,4.659-4.788 c1.325,0,2.463,0.099,2.795,0.143v3.24l-1.918,0.001c-1.504,0-1.795,0.715-1.795,1.763V11h4.44l-1,4h-3.44v9H22c1.105,0,2-0.895,2-2 V2C24,0.895,23.105,0,22,0z"
              ></path>
            </svg>
          </a>
          <a
            v-else-if="android"
            href="fb://page/215022017197560/"
            class="text-purple transition-colors duration-300 hover:text-mint"
          >
            <svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
              <path
                d="M22,0H2C0.895,0,0,0.895,0,2v20c0,1.105,0.895,2,2,2h11v-9h-3v-4h3V8.413c0-3.1,1.893-4.788,4.659-4.788 c1.325,0,2.463,0.099,2.795,0.143v3.24l-1.918,0.001c-1.504,0-1.795,0.715-1.795,1.763V11h4.44l-1,4h-3.44v9H22c1.105,0,2-0.895,2-2 V2C24,0.895,23.105,0,22,0z"
              ></path>
            </svg>
          </a>
          <a
            v-else
            href="https://www.facebook.com/Moovere-215022017197560/"
            class="text-purple transition-colors duration-300 hover:text-mint"
          >
            <svg viewBox="0 0 24 24" fill="currentColor" class="h-5">
              <path
                d="M22,0H2C0.895,0,0,0.895,0,2v20c0,1.105,0.895,2,2,2h11v-9h-3v-4h3V8.413c0-3.1,1.893-4.788,4.659-4.788 c1.325,0,2.463,0.099,2.795,0.143v3.24l-1.918,0.001c-1.504,0-1.795,0.715-1.795,1.763V11h4.44l-1,4h-3.44v9H22c1.105,0,2-0.895,2-2 V2C24,0.895,23.105,0,22,0z"
              ></path>
            </svg>
          </a>
        </div>
        <p class="mt-4 text-sm text-gray-800">
          ¡Ya estamos en redes sociales! <br />Síguenos para conocer más.
        </p>
      </div>
    </div>
    <div
      class="
        flex flex-col-reverse
        justify-between
        pt-5
        pb-10
        border-t
        lg:flex-row
      "
    >
      <p class="text-sm text-gray-600">
        © Moovere 2021. Todos los Derechos Reservados. Sitio hecho por
        <a href="https://www.cintatic.com/" class="text-gray-800"
          >cintatic.com</a
        >
      </p>
      <ul
        class="
          flex flex-col
          mb-3
          space-y-2
          lg:mb-0
          sm:space-y-0 sm:space-x-5 sm:flex-row
        "
      >
        <li>
          <a
            href="/pdf/politica_privacidad.pdf"
            class="
              text-sm text-gray-600
              transition-colors
              duration-300
              hover:text-purple
            "
            >Política de Privacidad</a
          >
        </li>
        <li>
          <a
            href="/pdf/terminos_condiciones.pdf"
            class="
              text-sm text-gray-600
              transition-colors
              duration-300
              hover:text-purple
            "
            >Terminos y Condiciones</a
          >
        </li>
      </ul>
    </div>
  </div>
</template>
<script>
export default {
  data() {
    return {
      ios: null,
      android: null,
    }
  },
  mounted() {
    if (navigator.userAgent.toLowerCase().includes('iphone')) this.ios = true
    if (navigator.userAgent.toLowerCase().includes('android'))
      this.android = true
  },
}
</script>
