<script setup>
import { RouterLink } from "vue-router";
import Gallery from "@/components/detail/Gallery.vue";
import About from "../components/detail/About.vue";
import Aside from "../components/detail/Aside.vue";
</script>

<template>
  <main>
    <div class="container p-2 mx-auto my-10 max-w-7xl">
      <div class="flex flex-row flex-wrap py-4">
        <main role="main" class="w-full px-4 pt-1 sm:w-2/3 md:w-2/3">
          <h1
            class="mb-2 text-3xl font-bold leading-normal tracking-tight text-gray-900 sm:text-4xl md:text-4xl"
          >
            RoboCrypto UI Kit
          </h1>
          <p class="text-gray-500">Build your next coin startup</p>
          <Gallery />
          <About />
        </main>
        <Aside />
      </div>
    </div>
  </main>
</template>
