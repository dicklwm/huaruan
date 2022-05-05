<!-- global-top.vue -->
<template>
  <footer
     v-if="$slidev.nav.currentLayout !== 'cover'"
  >
    <p class="absolute bottom-0 left-0 p-2">
      💪 MinLee
      <img src="/head.jpeg" class="w-4 inline-block rounded-1/2" alt="head">
    </p>
    <p
     class="absolute bottom-0 right-0 p-2"
    >
       {{ $slidev.nav.currentPage }} / {{ $slidev.nav.total }}
    </p>
  </footer>
</template>