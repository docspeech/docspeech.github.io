<template>
  <div>
    <NuxtLayout>
      <NuxtPage />
    </NuxtLayout>
  </div>
</template>

<script setup>
import { onMounted } from "vue";
import { useFlowbite } from "~/composables/useFlowbite";

// initialize components based on data attribute selectors
onMounted(() => {
  useFlowbite(() => {
    initFlowbite();
  });
});
</script>
