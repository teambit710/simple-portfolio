<template>
  <header class="text-gray-700 bg-blue-700 body-font">
    <div
      class="container flex flex-col flex-wrap items-center p-5 mx-auto md:flex-row"
    >
      <a
        class="flex items-center mb-4 font-medium text-gray-900 title-font md:mb-0"
      >
        <img class="h-10 logo" src="@/assets/logo_sm.png" alt="" />
        <span class="ml-3 text-xl nice">Ed's</span>
        <span class="text-xl text-white"> Web</span>
      </a>
      <nav
        class="flex flex-wrap items-center justify-center text-base md:ml-auto"
      >
        <nuxt-link to="/ideas/" class="mr-5 hover:text-gray-900"
          >Ideas</nuxt-link
        >
        <nuxt-link to="/skills/" class="mr-5 hover:text-gray-900"
          >Skills</nuxt-link
        >
        <nuxt-link to="/projects/" class="mr-5 hover:text-gray-900"
          >Project</nuxt-link
        >
        <nuxt-link to="/contact/" class="mr-5 hover:text-gray-900"
          >Contact</nuxt-link
        >
      </nav>
      <button
        class="inline-flex items-center px-3 py-1 mt-4 text-base bg-gray-200 border-0 rounded focus:outline-none hover:bg-gray-300 md:mt-0"
      >
        Button
        <svg
          fill="none"
          stroke="currentColor"
          stroke-linecap="round"
          stroke-linejoin="round"
          stroke-width="2"
          class="w-4 h-4 ml-1"
          viewBox="0 0 24 24"
        >
          <path d="M5 12h14M12 5l7 7-7 7"></path>
        </svg>
      </button>
    </div>
  </header>
</template>
<style scoped>
@keyframes logo-sm {
  0% {
    transform: rotate(0) scale(6) translateY(10%);
  }
  50% {
    transform: rotate(0) scale(1) translateY(10%);
  }
  60% {
    transform: rotate(0) scale(1.5) translateY(10%);
  }
  65% {
    transform: rotate(0) scale(1.3) translateY(10%);
  }
  70% {
    transform: rotate(0) scale(0.7) translateY(10%);
  }
  75% {
    transform: rotate(0) scale(1) translateY(0);
  }
  80% {
    transform: rotate(0) scale(1.2) translateY(0);
  }
  85% {
    transform: rotate(0) scale(1.5) translateY(0);
  }
  90% {
    transform: rotate(0) scale(1.2) translateY(0);
  }
  95% {
    transform: rotate(0) scale(1.5) translateY(0);
  }
  100% {
    transform: rotate(0) scale(1) translateY(0);
  }
}

.logo {
  animation: logo-sm 3s 1 0s ease-in;
}
page-enter-active,
.page-leave-active {
  transition: all 0.3s ease-out;
}
.page-enter,
.page-leave-active {
  opacity: 0;
  transform-origin: 50% 50%;
}
</style>
