<template>
  <div>
    <div class="bg-white mb-3">
      <PartialsTopHero />

      <PartialsBigCard />

      <div class="px-4 py-6">
        <ul class="grid grid-cols-2 gap-3 sm:gap-6 sm:grid-cols-4">
          <PartialsMenuCard v-for="(menuCard, index) in menuCards" :key="index" :menu-card="menuCard" />
        </ul>
      </div>

      <!-- Section Banner -->
      <div class="px-4 py-6">
        <PartialsHeroImage
          href="https://sembako.wargabantuwarga.com"
          alt="Ajukan bantuan sembako jika positif Covid-19 - Daftar Sekarang"
          img-src="banner-2.png"
        />
      </div>
    </div>

    <div class="bg-white mb-3">
      <!-- Section Informasi Terbaru -->
      <LandingInformasiTerbaru />
    </div>

    <div class="bg-white mb-3">
      <!-- Section Cara Berkontribusi -->
      <LandingCaraBerkontribusi />
    </div>

    <!-- Section Donasi Warga Terdampak -->
    <div class="bg-white mb-3">
      <LandingDonasiWarga />
    </div>

    <div class="bg-white mb-3">
      <div class="px-4 py-6">
        <PartialsHeroImage
          href="https://sembako.wargabantuwarga.com"
          alt="Telemedicine Gratis (Inisiatif Beberapa Dokter) - Cek Sekarang"
          img-src="banner-3.png"
        />
      </div>
    </div>

    <div class="bg-white mb-3">
      <LandingAplikasiPartner />
    </div>
  </div>
</template>

<script>
export default {
  name: 'IndexPage',
  data() {
    return {
      menuCards: [
        {
          svg: 'hospital.svg',
          href: '/provinces?kebutuhan=Rumah%20sakit',
          title: 'Rumah Sakit',
        },
        {
          svg: 'ambulance.svg',
          href: '/provinces?kebutuhan=Ambulans',
          title: 'Ambulans',
        },
        {
          svg: 'oxygen.svg',
          href: '/provinces?kebutuhan=Oksigen',
          title: 'Info Oksigen',
        },
        {
          svg: 'donor.svg',
          href: '/provinces?kebutuhan=Donor%20plasma',
          title: 'Donor',
        },
        {
          svg: 'education.svg',
          href: '/provinces?kebutuhan=Edukasi',
          title: 'Edukasi',
        },
        {
          svg: 'donation.svg',
          href: '/provinces?kebutuhan=Donasi',
          title: 'Donasi',
        },
        {
          svg: 'contribution.svg',
          href: '/provinces?kebutuhan=Kontribusi',
          title: 'Kontribusi',
        },
      ],
    }
  },
}
</script>
