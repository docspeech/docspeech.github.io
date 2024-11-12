<template>
  <div class="container mx-auto px-8">
    <div class="grid grid-cols-1 md:grid-cols-2 items-center mt-8">
      <div class="w-full">
        <NuxtImg
          src="/logo.png"
          width="365"
          class="mb-8"
          srcset="/logo.png 1x, /logo@2x.png 2x"
        ></NuxtImg>
        <h2 class="text-3xl font-bold mb-4">Read faster by listening</h2>
        <p class="mb-8 text-lg">
          Turn any document to audiobook with state-of-the art AI-based
          text-to-speech engine.
        </p>
        <NuxtLink
          to="https://play.google.com/store/apps/details?id=com.docspeech.docspeech&pli=1"
          class="inline-block mb-10"
        >
          <NuxtImg src="/google-play.png" width="250"></NuxtImg>
        </NuxtLink>
      </div>
      <div class="w-full">
        <NuxtImg
          class="w-full"
          src="/mockup.png"
          srcset="/mockup.png 1x, /mockup@2x.png 2x"
        ></NuxtImg>
      </div>
    </div>
  </div>
</template>
