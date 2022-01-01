<template>
  <div class="font-sans antialiased bg-gray-100">
    <PartialsMainNavbar />
    <div class="w-full sm:max-w-xl mx-auto my-16">
      <Nuxt />
    </div>
    <PartialsMainFooter />
  </div>
</template>

<script lang="ts">
export default {
  name: 'DefaultLayout',
}
</script>
