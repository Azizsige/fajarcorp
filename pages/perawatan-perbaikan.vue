<template>
  <div>
    <Navbar/>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-3xl">DUKUNGAN OPERASIONAL</h3>
      <div class="pt-8">
        Saat ini pelanggan dapat menghubungi kami kapan saja melalui Trakindo Call Center di 1500228 untuk mendapatkan bantuan dan saran segera dari Services Command Center dan Marine Command Center untuk kapal anda, kami memberikan layanan monitor alat berat saat itu juga sehingga pelanggan dapat membuat keputusan lebih cepat untuk mencapai produktivitas yang tinggi dari alat berat mereka.
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  RINCIAN
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Layanan Workshop</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Kami memiliki workshop yang lengkap dan canggih untuk melayani pekerjaan perbaikan dan pemeliharaan. Workshop kami menerapkan standar pengendalian pencemaran yang ketat dan telah memenangkan sertifikasi tingkat tinggi dari Caterpillar.<br><br>
                        Workshop kami dilengkapi dengan peralatan khusus seperti Engine Dyno Test Benches, Hydraulic Test Benches, Fuel Injection Test Benches, dan Hydraulic Track Presses untuk membantu alat berat anda bekerja dengan baik.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Servis di Lapangan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <div class="flex">
                          <div class="w-3/4 mr-2">
                            Teknisi kami tersedia untuk servis di lokasi dan servis darurat 24 jam sehari, 7 hari seminggu (beberapa lokasi sesuai dengan permintaan pelanggan) dan melayani cakupan lebih luas dengan adanya Resident Technician yang berada lebih dekat lagi dengan lokasi pelanggan. Para teknisi kami dilengkapi dengan peralatan khusus Caterpillar serta peralatan diagnostik dengan komputerisasi sehingga dapat memberikan diagnostik lebih cepat, perbaikan dan troubleshooting yang akurat serta penyediaan layanan informasi dan pemeriksaan untuk suku cadang yang tersedia.
                          </div>
                          <div class="w-3/12">
                            <img class="lg:h-64 md:h-56 sm:h-44 h-32 lg:w-64 md:w-56 sm:w-44 w-32"  src="https://www.trakindo.co.id/sites/default/files/inline-images/day13_BANGKA__151.jpg" alt="">
                          </div>
                        </div>
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Perbaikan Khusus</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Trakindo memiliki jaringan workshop khusus di seluruh Indonesia dimana teknisi yang terlatih menggunakan peralatan dan perangkat yang dapat memperbaiki dan memelihara alat berat anda. Tanpa harus mengirimkan alat berat anda kembali ke pabrik untuk servis, workshop kami dapat menghemat waktu dan uang Anda.
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
      <h3 class="lg:text-3xl">INSPEKSI</h3>
      <div class="pt-8">
        Inspeksi alat berat untuk mengidentifikasi kondisi kesehatan dan potensi masalah sebelum kerusakan sehingga dapat mengurangi masa downtime yang tidak terencana dan biaya untuk perbaikan.
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  RINCIAN
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Technical Analysis (TA)</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        TA adalah daftar aktivitas/checklist inspeksi yang digunakan untuk melakukan inspeksi kondisi alat berat secara visual atau menggunakan perangkat servis yang canggih untuk membantu mengidentifikasi backlog yang perlu dilakukan untuk meningkatkan atau mempertahankan kinerja alat berat.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Custom Track Service (CTS)</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <div class="flex">
                          <div class="w-3/4 mr-2">
                            Custom Track Service adalah program pengelolaan alat berat yang ditawarkan oleh Trakindo untuk membantu anda mendapatkan undercarriage yang maksimal sementara di waktu yang sama menghemat waktu dan biaya dengan:
                            <ul class="pl-10 pt-5 list-disc">
                              <li>Meningkatkan nilai built-in komponen undercarriage CAT®.</li>
                              <li>Menyediakan informasi analisa yang cepat dan akurat mengenai undercarriage yang digunakan.</li>
                              <li>Memungkinkan pelanggan untuk dapat mengambil keputusan mengenai pemeliharaan.</li>
                            </ul>
                          </div>
                          <div class="w-3/12">
                            <img class="lg:h-64 md:h-56 sm:h-44 h-32 lg:w-64 md:w-56 sm:w-44 w-32"  src="https://www.trakindo.co.id/sites/default/files/inline-images/day4kaltim_0111.jpg" alt="">
                          </div>
                        </div>
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">Custom Hydraulic Sservice (CHS)</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Inspeksi Custom Hydraulic Service membantu pemilik alat berat menjaga sistim hidrolik mereka bekerja secara sangat efisien. Direkomendasikan setahun sekali untuk setiap 2000 jam.
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
