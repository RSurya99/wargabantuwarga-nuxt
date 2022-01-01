<template>
  <div class="font-sans antialiased bg-gray-100">
    <PartialsMainTopbar />
    <div class="w-full sm:max-w-xl mx-auto my-16">
      <Nuxt />
    </div>
    <PartialsBottomNavbar />
  </div>
</template>

<script>
export default {
  name: 'DefaultLayout',
}
</script>
