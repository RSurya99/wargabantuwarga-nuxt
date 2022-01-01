<template>
  <section class="bg-white overflow-hidden px-4 py-6 space-y-4">
    <h2 class="text-lg sm:text-xl font-semibold">Informasi Terbaru</h2>
    <PartialsNewArticle v-for="(article, index) in articles" :key="index" :article="article" />
  </section>
</template>

<script>
export default {
  data() {
    return {
      articles: [
        {
          title: 'Rumah Oksigen Gotong Royong (ROGR)',
          date: '4 Agustus 2021',
          description: `Pendaftaran Rumah Oksigen Gotong Royong (ROGR) telah dibuka. ROGR adalah fasilitas kesehatan semi-permanen
            yang khusus dilengkapi dengan peralatan suplai oksigen dan tempat tidur perawatan bagi warga terpapar
            COVID-19 dengan gejala ringan.`,
          linkTitle: 'Daftar ROGR di aplikasi Halodoc',
          link: 'https://halodoc.page.link/gpbaUJdzJM3UrRQp9',
        },
        {
          title: 'Wilayah Jakarta',
          date: '25 Juli 2021',
          description: `Daftar Vaksin di Sentra Vaksinasi SINERGI SEHAT untuk masyarakat usia 12 tahun ke atas. Pelaksanaan Vaksin pada 22 Juli-15 September 2021 (Senin-Jumat pukul 08.30-15.00 WIB). Lokasi pelasanaan di The Media Hotel & Towers (Jln. Gunung Sahari No. 3, RT 16/RW 3, Gunung Sahari).`,
          linkTitle: 'Daftar vaksin SINERGI SEHAT',
          link: 'https://sinergisehat.vaksin.siapdok.id/#/',
        },
        {
          title: 'Kementerian Kesehatan',
          date: '14 Juli 2021',
          description: `Kementerian Kesehatan meluncurkan SIRANAP terbaru versi 3.0. Melalui SIRANAP 3.0, kita dapat memeriksa ketersediaan IGD di seluruh Indonesia. Khusus untuk wilayah Jakarta ketersediaan IGD diperbarui setiap 3 jam sekali oleh para relawan lapangan.`,
          linkTitle: 'Cek ketersediaan IGD Jakarta',
          link: 'https://yankes.kemkes.go.id/app/siranap/rumah_sakit?jenis=1&propinsi=31prop&kabkota=',
        },
      ],
    }
  },
}
</script>
