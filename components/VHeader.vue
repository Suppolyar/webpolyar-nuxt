<template>
  <div>
    <div>
      <nav class="bg-gray-800">
        <div class="container mx-auto px-4">
          <div class="flex items-center justify-between h-16">
            <div class="flex items-center">
              <NuxtLink to="/">
                <div class="flex-shrink-0">
                  <img
                    class="w-40"
                    src="@/static/main-logo-white.svg"
                    alt="Workflow logo"
                  >
                </div>
              </NuxtLink>
              <div class="hidden md:block">
                <div class="ml-10 flex items-baseline">
                  <NuxtLink
                    to="/"
                    class="ml-4 px-3 py-2 rounded-md text-base font-medium text-gray-300 transition duration-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
                  >
                    Обо мне
                  </NuxtLink>
                  <NuxtLink
                    to="/portfolio"
                    class="ml-4 px-3 py-2 rounded-md text-base font-medium text-gray-300 transition duration-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
                  >
                    Портфолио
                  </NuxtLink>
                  <NuxtLink
                    to="/blog"
                    class="ml-4 px-3 py-2 rounded-md text-base font-medium text-gray-300 transition duration-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
                  >
                    Блог
                  </NuxtLink>
                  <NuxtLink
                    to="/contacts"
                    class="ml-4 px-3 py-2 rounded-md text-base font-medium text-gray-300 transition duration-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
                  >
                    Контакты
                  </NuxtLink>
                </div>
              </div>
            </div>
            <div class="-mr-2 flex md:hidden">
              <!-- Mobile menu button -->
              <button
                class="inline-flex items-center bg-gray-500 justify-center p-2 rounded-md text-gray-400 hover:text-white hover:bg-gray-300 focus:outline-none focus:bg-gray-300 focus:text-white"
                @click="toggle"
              >
                <svg
                  :class="[isOpen ? 'hidden' : 'block', 'h-6 w-6']"
                  stroke="currentColor"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M4 6h16M4 12h16M4 18h16"
                  />
                </svg>
                <svg
                  :class="[isOpen ? 'block' : 'hidden', 'h-6 w-6']"
                  stroke="currentColor"
                  fill="none"
                  viewBox="0 0 24 24"
                >
                  <path
                    stroke-linecap="round"
                    stroke-linejoin="round"
                    stroke-width="2"
                    d="M6 18L18 6M6 6l12 12"
                  />
                </svg>
              </button>
            </div>
          </div>
        </div>
        <div :class="[isOpen ? '' : 'hidden', 'md:hidden']">
          <div class="px-2 pt-2 pb-3 sm:px-3">
            <NuxtLink
              to="/"
              class="block px-3 py-2 rounded-md text-base font-medium text-white focus:outline-none focus:text-white focus:bg-gray-700"
            >
              Обо мне
            </NuxtLink>
            <NuxtLink
              to="/portfolio"
              class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
            >
              Портфолио
            </NuxtLink>
            <NuxtLink
              to="/blog"
              class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
            >
              Блог
            </NuxtLink>
            <NuxtLink
              to="/contacts"
              class="mt-1 block px-3 py-2 rounded-md text-base font-medium text-gray-300 hover:text-white hover:bg-gray-700 focus:outline-none focus:text-white focus:bg-gray-700"
            >
              Контакты
            </NuxtLink>
          </div>
        </div>
      </nav>
    </div>
  </div>
</template>

<script>
export default {
  data () {
    return {
      isOpen: false
    }
  },
  methods: {
    toggle () {
      this.isOpen = !this.isOpen
    }
  }
}
</script>
