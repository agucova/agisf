<script setup lang="ts">
// https://github.com/vueuse/head
// you can use this to manipulate the document head in any components,
// they will be rendered correctly in the html results with vite-ssg
useHead({
  title: 'AGI Safety Fundamentals @ UC Chile',
  meta: [
    { name: 'description', content: 'Un programa intensivo en seguridad de la IA.' },
    {
      name: 'theme-color',
      content: () => '#0D1628',
    },
  ],
  link: [
    {
      rel: 'icon',
      type: 'image/svg+xml',
      href: () => 'favicon.svg',
    },
  ],
})
</script>

<template>
  <RouterView />
</template>
