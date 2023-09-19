<script setup lang="ts">
// Use JS file on head like this:
useHead({
  link: [
    {
      rel: "modulepreload",
      href: "/js/app-b4670975.js",
    },
    {
      rel: "modulepreload",
      href: "/js/tailwind.config-687e688e.js",
    },
    {
      rel: "modulepreload",
      href: "/js/tailwind.config-687e688e.js",
    },
    {
      rel: "modulepreload",
        href: "/js/apexcharts.common-2171691b.js", 
    },
    {
      rel: "stylesheet",
      href: "/css/app.css",
    },
  ],
  script: [
    {
      type: "module",
      src: "/js/index-57787c39.js",
      tagPosition: "bodyClose",
    },
  ],
});
</script>

<template>
  <div>
    <!-- navbar  -->
    <Navbar />
    <slot></slot>
  </div>
</template>
