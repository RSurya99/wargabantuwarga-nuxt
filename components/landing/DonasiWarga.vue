<template>
  <section class="overflow-hidden px-4 py-6 pb-4 space-y-4">
    <h2 class="text-lg sm:text-xl font-semibold">Donasi Warga Terdampak</h2>
    <div class="grid grid-cols-2 gap-4">
      <div class="flex flex-col shadow-md rounded-md overflow-hidden max-w-xs">
        <div class="flex-shrink-0">
          <div class="inline-block max-w-full overflow-hidden relative box-border m-0">
            <div class="box-border block max-w-full">
              <img alt="" aria-hidden="true" :src="require('@/assets/img/card/card-image1.jpg')" />
            </div>
          </div>
        </div>
        <div class="p-3 space-y-1 h-0 flex-1">
          <p class="text-gray-500 text-xs sm:text-sm">COVID-19</p>
          <h3 class="font-semibold text-gray-700 text-sm sm:text-base">
            Donasi untuk berbagai kebutuhan (RS, puskesmas, nakes, dan warga terdampak)
          </h3>
        </div>
        <div class="p-3 justify-center">
          <a
            class="flex flex-row px-2.5 py-1.5 text-xs rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 font-normal"
            data-testid="donation-button-Donasi untuk berbagai kebutuhan (RS, puskesmas, nakes, dan warga terdampak)"
            href="https://kitabisa.com/campaign/daruratcovid2021"
            rel="nofollow noopener noreferrer"
            target="_blank"
            >Donasi Sekarang</a
          >
        </div>
      </div>
      <div class="flex flex-col shadow-md rounded-md overflow-hidden max-w-xs">
        <div class="flex-shrink-0">
          <div class="inline-block max-w-full overflow-hidden relative box-border m-0">
            <div class="box-border block max-w-full">
              <img
                class="max-w-full block m-0 border-none p-0"
                alt=""
                aria-hidden="true"
                :src="require('@/assets/img/card/card-image2.jpg')"
              />
            </div>
          </div>
        </div>
        <div class="p-3 space-y-1 h-0 flex-1">
          <p class="text-gray-500 text-xs sm:text-sm">COVID-19</p>
          <h3 class="font-semibold text-gray-700 text-sm sm:text-base">Donasi untuk Inisiatif #WargaBantuWarga</h3>
        </div>
        <div class="p-3 justify-center">
          <a
            class="flex flex-row px-2.5 py-1.5 text-xs rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-white bg-blue-700 hover:bg-blue-800 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75 font-normal"
            data-testid="donation-button-Donasi untuk Inisiatif #WargaBantuWarga"
            href="https://kitabisa.com/campaign/wargabantuwarga"
            rel="nofollow noopener noreferrer"
            target="_blank"
            >Donasi Sekarang</a
          >
        </div>
      </div>
    </div>
    <div class="p-4 text-center space-y-3">
      <h3 class="text-blue-700 leading-5 font-semibold">
        <a href="/donasi">Lihat Selengkapnya</a>
      </h3>
    </div>
  </section>
</template>
