<template>
  <div>
    <!-- Section Banner -->
    <section class="relative">
      <img :src="require('@/assets/img/hero-banner.png')" alt="" />
      <div class="w-full h-full p-4 absolute top-0 flex flex-col flex-1 items-start justify-between">
        <img :src="require('@/assets/img/logo/logo.svg')" class="h-8 h-10" alt="" />
        <div class="w-[60%] sm:w-[55%] space-y-1">
          <h1 class="text-blue-700 text-lg sm:text-2xl">Warga<span class="font-semibold">Bantu</span>Warga</h1>
          <p class="text-xs sm:text-sm">
            Inisiatif warga untuk berbagi informasi dan membantu warga yang terdampak Covid-19.
          </p>
        </div>
      </div>
    </section>

    <!-- Section Telusuri Sekarang -->
    <section class="px-4 py-8">
      <h2 class="text-lg sm:text-xl font-semibold sm:mx-6 text-center">
        Cek database RS, Puskesmas, Ambulans, Oksigen, dan kontak penting lainnya
      </h2>
      <a
        class="flex flex-row px-4 py-2 text-base rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 mt-4 cursor-pointer"
        >Telusuri sekarang</a
      >
    </section>
  </div>
</template>
