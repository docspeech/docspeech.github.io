<template>
  <div class="container mx-auto flex flex-col items-center md:flex-row md:justify-center gap-3 md:gap-6 my-10">
    <NuxtLink v-for="link in links" :key="link.url" :to="link.url" class="text-violet-800 hover:underline">
      {{ link.text }}</NuxtLink
    >
  </div>
</template>
<script setup>
const links = ref([
  { url: "/privacy", text: "Privacy Policy" },
  { url: "/terms", text: "Terms of Service" },
  { url: "mailto:app.docspeech@gmail.com", text: "Contact Us" },
]);
</script>
