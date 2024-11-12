<template>
  <div class="container mx-auto px-4 py-4">
    <h1>Delete Account</h1>

    <div
      class="flex items-center p-4 mb-4 text-sm text-red-800 border border-red-300 rounded-lg bg-red-50"
      role="alert"
    >
      <svg
        class="flex-shrink-0 inline w-4 h-4 me-3"
        aria-hidden="true"
        xmlns="http://www.w3.org/2000/svg"
        fill="currentColor"
        viewBox="0 0 20 20"
      >
        <path
          d="M10 .5a9.5 9.5 0 1 0 9.5 9.5A9.51 9.51 0 0 0 10 .5ZM9.5 4a1.5 1.5 0 1 1 0 3 1.5 1.5 0 0 1 0-3ZM12 15H8a1 1 0 0 1 0-2h1v-3H8a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1v4h1a1 1 0 0 1 0 2Z"
        />
      </svg>
      <span class="sr-only">Info</span>
      <div>
        <span class="font-medium">Danger alert!</span> This will remove your
        account along with all your drawing progresses and subscription
        information. This is not reversible. You can create a new account at any
        time but your deleted information will not be recovered.
      </div>
    </div>
    <div>
      If you want to delete your account, please contact us with your email
      address at
      <NuxtLink
        to="mailto:app.docspeech@gmail.com"
        class="text-violet-800 hover:underline"
        >app.docspeech@gmail.com</NuxtLink
      >.
    </div>
  </div>
</template>

<style scoped>
p {
  @apply mb-8;
}
h1 {
  @apply text-4xl font-bold mb-4;
}
h2 {
  @apply text-2xl mt-4 mb-2 font-semibold;
}
h3 {
  @apply text-xl mt-2 mb-2 font-semibold;
}
h4 {
  @apply text-lg mt-2 mb-2;
}
ul {
  @apply list-disc ml-4 mb-4;
}
</style>
