<template>
  <ul
    class="font-medium flex flex-col p-4 md:p-0 mt-4 border border-black border-opacity-20 rounded-lg md:flex-row md:space-x-8 rtl:space-x-reverse md:mt-0 md:border-0"
  >
    <li v-for="link in links">
      <NuxtLink
        :key="link.url"
        :to="link.url"
        class="block py-2 px-3 text-gray-900 rounded hover:bg-violet-200 md:hover:bg-transparent md:border-0 md:hover:text-violet-800 md:p-0"
        >{{ link.text }}</NuxtLink
      >
    </li>
  </ul>
</template>
<script setup>
const links = ref([
  { url: "/", text: "Home" },
  { url: "/privacy", text: "Privacy Policy" },
  { url: "/terms", text: "Terms & Conditions" },
  { url: "/delete", text: "Delete Account" },
  { url: "mailto:app.docspeech@gmail.com", text: "Contact Us" },
]);
</script>
<style scoped>
.router-link-active {
  @apply text-white bg-violet-700 md:bg-transparent md:text-violet-800;
}
</style>
