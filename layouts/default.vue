<template>
  <div class="min-h-screen overflow-hidden">
    <TheBanner />

    <Nuxt />

    <TheFooter />
  </div>
</template>

<style>
html {
  scroll-behavior: smooth;
}

body {
  @apply bg-white;
  @apply text-coolGray-600;
}

.js-focus-visible :focus:not(.focus-visible) {
  @apply outline-none;
}
</style>

<style scoped>
.page-enter-active,
.page-leave-active {
  @apply transition-opacity;
  @apply duration-150;
}

.page-enter,
.page-leave-to {
  @apply opacity-0;
}
</style>
