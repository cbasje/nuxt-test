<template>
  <div class="container dark:bg-gray-800">
    <div>
      <Logo />
      <h1 class="title dark:text-white">nuxt-test</h1>
      <div class="links">
        <a
          href="https://nuxtjs.org/"
          target="_blank"
          class="
            inline-flex
            justify-center
            rounded-md
            border border-gray-300
            dark:border-gray-700
            shadow-sm
            px-4
            py-2
            bg-white
            dark:bg-black
            text-sm
            font-medium
            text-gray-700
            dark:text-gray-300
            hover:bg-gray-50
            dark:hover:bg-gray-800
            focus:outline-none
            focus:ring-2
            focus:ring-offset-2
            focus:ring-offset-gray-100
            dark:focus:ring-offset-gray-900
            focus:ring-green-500
            dark:focus:ring-green-500
          "
        >
          Documentation
        </a>
        <a
          href="https://github.com/nuxt/nuxt.js"
          target="_blank"
          class="
            inline-flex
            justify-center
            rounded-md
            border border-gray-300
            dark:border-gray-700
            shadow-sm
            px-4
            py-2
            bg-white
            dark:bg-black
            text-sm
            font-medium
            text-gray-700
            dark:text-gray-300
            hover:bg-gray-50
            dark:hover:bg-gray-800
            focus:outline-none
            focus:ring-2
            focus:ring-offset-2
            focus:ring-offset-gray-100
            dark:focus:ring-offset-gray-900
            focus:ring-green-500
            dark:focus:ring-green-500
          "
        >
          GitHub
        </a>
      </div>
    </div>
  </div>
</template>

<script lang="ts">
import Vue from 'vue'

export default Vue.extend({})
</script>

<style lang="postcss">
.container {
  @apply min-h-screen min-w-full
    flex
    justify-center
    items-center
    text-center
    mx-auto;
}

.title {
  @apply text-7xl;
}

/* .links > button,
.links > a {
  @apply ;
} */
</style>
