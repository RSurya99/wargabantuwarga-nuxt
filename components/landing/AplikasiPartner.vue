<template>
  <div class="px-4 py-6 text-center overflow-hidden space-y-4">
    <h2 class="font-semibold">
      Download aplikasi telemedicine yang <br />
      didukung Kemenkes:
    </h2>
    <ul class="grid grid-cols-2 gap-2 sm:gap-4 sm:grid-cols-4">
      <li
        v-for="(sponsor, index) in sponsors"
        :key="index"
        class="inline-flex flex-col items-center justify-center text-center relative"
      >
        <a
          href="https://bit.ly/alodokter-isoman"
          class="border-solid border-2 border-gray-300 border-opacity-75 rounded-lg hover:border-blue-700 min-w-full h-20 relative"
          target="_blank"
        >
          <div class="inline-block max-w-full box-border">
            <div class="box-border block max-w-full">
              <img
                :src="require(`@/assets/img/sponsor/${sponsor.img}`)"
                :alt="sponsor.alt"
                class="rounded-md absolute top-0 bottom-0 left-0 right-0 box-border px-6 m-auto block object-contain min-w-full max-w-full min-h-full max-h-full"
              />
            </div>
          </div>
        </a>
      </li>
    </ul>
    <div class="p-4 bg-blue-50 text-center rounded-md space-y-3">
      <p class="text-base leading-6 font-semibold">
        Butuh Konseling Bagi Pasien, Keluarga Pasien, atau Tenaga Kesehatan Terdampak COVID-19?
      </p>
      <a
        class="flex flex-row px-4 py-2 text-base rounded-full items-center justify-center border border-transparent font-medium shadow-sm focus:outline-none focus:ring-2 focus:ring-offset-2 text-blue-700 border-blue-700 hover:bg-blue-100 focus:ring-blue-700 disabled:cursor-not-allowed disabled:opacity-75"
        href="/telekonseling"
        >Lihat daftar di sini</a
      >
    </div>
  </div>
</template>

<script>
export default {
  data() {
    return {
      sponsors: [
        {
          img: 'Alodokter.png',
          alt: 'Alodokter',
        },
        {
          img: 'Halodoc.png',
          alt: 'Halodoc',
        },
        {
          img: 'Getwell.png',
          alt: 'Getwell',
        },
        {
          img: 'Klinikgo.png',
          alt: 'Klinikgo',
        },
        {
          img: 'Klikdokter.png',
          alt: 'Klikdokter',
        },
        {
          img: 'GrabHealth.png',
          alt: 'GrabHealth',
        },
        {
          img: 'LinkSehat.png',
          alt: 'LinkSehat',
        },
        {
          img: 'GoodDoctor.png',
          alt: 'GoodDoctor',
        },
        {
          img: 'Milvik.png',
          alt: 'Milvik',
        },
        {
          img: 'Prosehat.png',
          alt: 'Prosehat',
        },
        {
          img: 'SehatQ.png',
          alt: 'SehatQ',
        },
        {
          img: 'YesDok.png',
          alt: 'YesDok',
        },
      ],
    }
  },
}
</script>
