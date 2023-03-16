<script lang="ts" setup>
import { ref } from "vue";

defineProps<{ msg: string }>();

const count = ref(0);
</script>

<template>
  <h1
    class="bg-gradient-to-r from-green-600 to-sky-400 bg-clip-text text-5xl font-black text-transparent selection:bg-transparent"
  >
    {{ msg }}
  </h1>

  <p class="mt-6 space-x-4">
    Recommended IDE setup:
    <a
      class="text-emerald-500 underline transition-all hover:text-emerald-400"
      href="https://www.jetbrains.com/pt-br/webstorm/"
      target="_blank"
      >WebStorm</a
    >
  </p>

  <p class="mt-4 space-x-4">
    <a
      class="text-emerald-500 underline transition-all hover:text-emerald-400"
      href="https://vitejs.dev/guide/features.html"
      target="_blank"
      >Vite Docs</a
    >
    <span>|</span>
    <a
      class="text-emerald-500 underline transition-all hover:text-emerald-400"
      href="https://v3.vuejs.org/guide/"
      target="_blank"
      >Vue 3 Docs</a
    >
    <span>|</span>
    <a
      class="text-emerald-500 underline transition-all hover:text-emerald-400"
      href="https://www.typescriptlang.org/docs/"
      target="_blank"
      >Typescript Docs</a
    >
    <span>|</span>
    <a
      class="text-emerald-500 underline transition-all hover:text-emerald-400"
      href="https://tailwindcss.com/docs/"
      target="_blank"
      >Tailwind CSS Docs</a
    >
  </p>

  <button
    class="my-6 rounded bg-gray-300 px-4 py-2 transition-all hover:bg-gray-200"
    type="button"
    @click="count++"
  >
    count is: {{ count }}
  </button>
  <p>
    Edit
    <code class="text-gray-400">components/HelloWorld.vue</code> to test hot
    module replacement.
  </p>
  <div class="mt-4 flex items-center justify-center space-x-4">
    <p class="">powered by</p>
    <img alt="ok" src="@/assets/brand-alitec.png" />
  </div>
</template>

<style scoped></style>
