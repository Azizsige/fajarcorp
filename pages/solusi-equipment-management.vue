<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <h3 class="lg:text-3xl">SOLUSI EQUIPMENT MANAGEMENT (EM SOLUTIONS)</h3>
        <div class="pt-8">
          Program ini adalah rangkaian layanan yang diintegrasikan menjadi solusi dan menyediakan beberapa level layanan dukungan serta dimodifikasi agar dapat memenuhi kebutuhan pelanggan. Solusi EM adalah cara Trakindo untuk menjalin kerjasama guna mencapai kesuksesan pelanggan. Kami adalah ahli di industri ini untuk Solusi Equipment Management yang telah dikenal memiliki nilai tinggi dan memerlukan opsi yang diinginkan oleh para pelanggan. Setiap operasional pelanggan memiliki tantangan yang unik dari kebutuhan produksi, fleet match, hingga ke pemeliharaan dan biaya operasional yang rendah. Kami dapat menyediakan teknologi dan layanan yang dapat diukur dan dimodifikasi untuk menyesuaikan dengan kebutuhan pelanggan. Dengan terhubungnya ke unit-unit alat berat melalui Solusi EM, Trakindo dapat menjadi lebih responsif terhadap kebutuhan, proaktif dalam memberikan rekomendasi pemeliharaan dan opsi perbaikan yang pre-priced, serta konsultatif dengan memberikan dukungan strategis dan anjuran. Melalui solusi EM, Trakindo dapat melakukan:
          <ol class="pl-10 pt-5 list-decimal">
            <li>Memberikan notifikasi alert berikut rekomendasinya berkaitan dengan indikasi kesehatan dari aset yang terhubung;</li>
            <li>Memberikan saran dan/atau bantuan dengan strategi pemeliharaan serta kinerjanya bila diperlukan;</li>
            <li>Manajemen kegiatan pemeliharaan dengan bermitra bersama pelanggan. Dari strategi, perencanaan &amp; pengawasan di lokasi pelanggan besertaeksekusinya.</li>
          </ol>
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
                  KEUNTUNGAN DARI SOLUSI EM
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Pengendalian Biaya</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Pemeliharaan yang terjadwal mengurangi biaya pemeliharaan secara keseluruhan dan juga mengurangi biaya per ton/BCM/kWh/etc. karena alat berat dapat diandalkan dan siap kerja. Solusi EM selaras dengan praktek pemeliharaan yang terjadwal.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Operasional Meningkat</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Mengetahui di mana alat berat tersebut berada dan apa yang sedang dikerjakannya memungkinkan pelanggan untuk fokus pada pemanfaatan yang efisien serta mengurangi pemborosan bahan bakar dan keausan. Peningkatan penggunaan alat berat pada pada pekerjaan yang produktif tentunya meningkatkan keuntungan.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Mengelola Karyawan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Peningkatan pada pemeliharaan yang dijawalkan memberikan masa produksi yang dapat direncanakan (mengurangi kerusakan) dan mendukung peningkatan efisiensi karyawan melalui utilisasi karyawan yang lebih tinggi baik untuk kebutuhan pemeliharaan dan operasional. Lebih banyak yang dapat dihasilkan dengan upaya yang lebih sedikit juga mengurangi biaya tenaga kerja secara keseluruhan.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Mengurangri Resiko</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Skala dari solusi EM menjadikan pelanggan mengalihkan resikonya ke Trakindo tergantung pada tingkat dukungan dari solusi yang ditawarkan. Semakin banyak tanggung jawab yang Trakindo miliki, makin tinggi tingkat resiko yang Trakindo ambil dari pelanggan.
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <hr class="bg-gray-300 p-3">
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-4xl font-bold">LIMA TINGKAT DARI SOLUSI EM</h3>
      <div class="pt-8">
        Lima tingkat dari Solusi EM – menyediakan solusi dukungan yang dibutuhkan pelanggan, tersedia dari level dasar sampai dengan level kontrak pemeliharaan lengkap.
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs_2(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  KEUNTUNGAN DARI SOLUSI EM
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab_2 !== 1, 'block': openTab_2 === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Level 1. ACCESS</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Connectivity to the asset is the key here. Providing the customer access to asset location and electronic data through Product Link (PL) hardware and Vision Link (VL) Software. SMS alerts for critical issues is part of this solution plus yearly inspections.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Level 2. INFORM</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Provides information from one or two connectivity options including Scheduled Oil Sampling (SOS), 3rd party Telematics and/or PL/VL inclusive of monthly reports detailing fuel burn (if available), productivity and issues reported.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Level 3. ADVISE</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Is the beginning of condition monitoring so requires SOS and electronic connectivity. More regular inspections with backlog repairs monitored, maintenance activity recorded (where possible) and scheduling advise provided inclusive of component lifecycle optimisation based on condition data (dependent on data quality and frequency).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Level 4. SUPPORT</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Moves into contracted scaled support solutions with Trakindo partnering the customer in the provision of maintenance activities, be they strategic, planning, condition monitoring, site operational support, execution, risk partnering or any combination of these. Trakindo is ready to provide the level of support in a bundled solution fully focused on the needs of the customer.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Level 5. MANAGE</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Is the solution where Trakindo takes responsibility for most if not all of the maintenance activities under contract for a known cost. The customer can focus on their areas of expertise, production and operation, while Trakindo manages the maintenance effort.
                      </div>
                    </div>
                  </div>
                </div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'SolusiEquipmentManagement',
  data () {
    return {
      title: 'Solusi Equipment Management - Fajar Corp',
      openTab: 1,
      openTab_2: 1
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
    },
    toggleTabs_2: function(tabNumber) {
      this.openTab_2 = tabNumber
    }
  }
}
</script>
