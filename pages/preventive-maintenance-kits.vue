<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <h3 class="lg:text-3xl">APAKAH PREVENTIVE MAINTENANCE KITS?</h3>
        <div class="pt-8">
          Preventive Maintenance Kits adalah sebuah paket suku cadang dan komponen yang dibutuhkan oleh alat berat anda dalam perawatan untuk mencegah kerusakan dengan biaya lebih rendah dibandingkan dengan membeli satuan. Kami memliki stok Preventive Maintenance Kits untuk setiap model dan seri alat berat, informasikan model dan tipe alat berat anda, kami akan langsung mengirimkannya.
        </div>
      </div>
    </div>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  MENGAPA PREVENTIVE MAINTENANCE KITS?
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Hemat Waktu</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <ul class="pl-10 list-disc">
                          <li>Paket perawatan direkomendasikan untuk setiap interval perawatan.</li>
                          <li>Semua yang Anda butuhkan untuk perawatan ada dalam satu paket.</li>
                          <li>Pemesanan yang mudah, hanya satu part number.</li>
                          <li>Sudah termasuk panduan perawatan.</li>
                        </ul>
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Hemat Biaya</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <ul class="pl-10 list-disc">
                          <li>Lebih terjangkau hingga 40% dibanding membeli satuan.</li>
                        </ul>
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Reliable</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <ul class="pl-10 list-disc">
                          <li>Suku cadang Cat asli.</li>
                          <li>Termasuk Filter Oli Cat, Filter Bahan Bakar Cat, Filter Hidrolis Cat, Seals, dan Gasket.</li>
                        </ul>
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
      Anda hanya membutuhkan satu part number untuk mendapatkan semua yang dibutuhkan untuk perawatan lengkap alat berat anda.
    </div>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'PreventiveMaintenanceKits',
  data () {
    return {
      title: 'Preventive Maintenance Kits - Fajar Corp',
      openTab: 1
    }
  },
  head () {
    return {
      title: this.title,
      meta: [
        {
          hid: 'description',
          name: 'description',
          content: 'Fajar Corp - Melayani Dengan Teknologi, Mutu, dan Harga Terbaik'
        }
      ]
    }
  },
  methods: {
    toggleTabs: function(tabNumber) {
      this.openTab = tabNumber
    }
  }
}
</script>
