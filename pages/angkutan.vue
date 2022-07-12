<template>
  <div>
    <Navbar/>
    <div class="container mx-auto lg:mb-32 md:mb-16 mb-8 px-8">
      <h2 class="lg:text-6xl text-yellow-400 font-bold lg:mb-64 md:mb-32 sm:mb-16 mb-8">ANGKUTAN</h2>
      <a class="bg-yellow-400 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded" href="#">Request Quote</a>
    </div>
    <div class="bg-gray-300">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <h3 class="lg:text-4xl font-bold">ANGKUTAN</h3>
        <div class="pt-8">
          Indonesia memiliki kekayaan hasil hutan yang luar biasa. Seiring dengan perkembangan pengelolaan hutan yang terpadu dan berwawasan hijau, ada empat segment utama di dalam pengelolaan manfaat hasil hutan di Indonesia, baik itu Hutan Alam ataupun Hutan Tanaman Industri. Pada setiap segmen, Trakindo turut berpartisipasi membantu usaha di bidang kehutanan untuk menjadi lebih efektif dan efisien, dari mulai tahap pembukaan lahan sampai ke dukungan di operasi Mill Yard. We are ready to advance your business forward.
        </div>
      </div>
    </div>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-4xl font-bold">RANTAI NILAI ANGKUTAN</h3>
      <div class="pt-8">
        Indonesia memiliki kekayaan hasil hutan yang luar biasa. Seiring dengan perkembangan pengelolaan hutan yang terpadu dan berwawasan hijau, ada empat segment utama di dalam pengelolaan manfaat hasil hutan di Indonesia, baik itu Hutan Alam ataupun Hutan Tanaman Industri. Pada setiap segmen, Trakindo turut berpartisipasi membantu usaha di bidang kehutanan untuk menjadi lebih efektif dan efisien, dari mulai tahap pembukaan lahan sampai ke dukungan di operasi Mill Yard. We are ready to advance your business forward.
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(2)" v-bind:class="{'text-black bg-yellow-400': openTab !== 2, 'text-black bg-white': openTab === 2}">
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(3)" v-bind:class="{'text-black bg-yellow-400': openTab !== 3, 'text-black bg-white': openTab === 3}">
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
            </ul>
            <div class="relative flex flex-col min-w-0 break-words bg-white w-full mb-6">
              <div class="px-4 flex-auto">
                <div class="tab-content tab-space">
                  <div v-bind:class="{'hidden': openTab !== 1, 'block': openTab === 1}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Infrastruktur</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Sebelum pengambilan pohon dari daerah penanaman, hal pertama yang harus dibangun adalah akses jalan, kanal, tempat tinggal untuk pekerja dan bengkel untuk peralatan dan alat-alat pemeliharaan. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan persiapan infrastruktur menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Pemanenan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji, felling head, atau harvester head. Kayu log kemudian dibersihkan dari cabang-cabangnya dengan menggunakan parang, gergaji, atau harvester head. Setelah ditebang, kontraktor akan menyediakan debarked log jika diminta oleh pembeli. Log kemudian dipotong dengan panjang standar tertentu. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan pemanenan menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Ekstraksi</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN (tempat penimbunan kayu) selain hauling road menggunakan perahu, skidder, forwarder atau “sampan darat” – modifikasi excavator dengan penyimpanan log di belakang untuk mengekstrak log. PT Trakindo Utama memiliki pilihan unit yang terbaik untuk kegiatan ekstraksi menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Fixed Grapple atau menggunakan Cat Wheel Skidder 525.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Pengolahan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap panen, akan dilakukan debarked dengan menggunakan processing head, atau menggunakan metodologi lain selama diterima oleh pembeli. Hasil dari tahap ini adalah semua log telah memenuhi panjang yang telah ditentukan dan sudah dalam kondisi debarked. Untuk kegiatan pengolahan, PT Trakindo Utama memiliki pilihan unit yang terbaik menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Penumpukan / Pemuatan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan kemudian ditumpuk di TPN (tempat penimbunan kayu). Log kemudian dimuat ke truk untuk pengiriman ke tempat penimbunan pabrik atau kadang-kadang langsung diumpankan ke tempat pengumpan. Kami menyediakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Randall Rotating Grapple, atau Fixed Grapple untuk aplikasi penyusunan atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill Yard</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan pabrik pulp dapat beroperasi terus menerus. Cat 320DFM untuk operasi di Mill Yard merupakan pilihan terbaik.
                      </div>
                    </div>
                  </div>
                  <div v-bind:class="{'hidden': openTab !== 2, 'block': openTab === 2}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Infrastruktur</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Sebelum pengambilan pohon dari daerah penanaman, hal pertama yang harus dibangun adalah akses jalan, kanal, tempat tinggal untuk pekerja dan bengkel untuk peralatan dan alat-alat pemeliharaan. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan persiapan infrastruktur menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Pemanenan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji, felling head, atau harvester head. Kayu log kemudian dibersihkan dari cabang-cabangnya dengan menggunakan parang, gergaji, atau harvester head. Setelah ditebang, kontraktor akan menyediakan debarked log jika diminta oleh pembeli. Log kemudian dipotong dengan panjang standar tertentu. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan pemanenan menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Ekstraksi</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN (tempat penimbunan kayu) selain hauling road menggunakan perahu, skidder, forwarder atau “sampan darat” – modifikasi excavator dengan penyimpanan log di belakang untuk mengekstrak log. PT Trakindo Utama memiliki pilihan unit yang terbaik untuk kegiatan ekstraksi menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Fixed Grapple atau menggunakan Cat Wheel Skidder 525.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Pengolahan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap panen, akan dilakukan debarked dengan menggunakan processing head, atau menggunakan metodologi lain selama diterima oleh pembeli. Hasil dari tahap ini adalah semua log telah memenuhi panjang yang telah ditentukan dan sudah dalam kondisi debarked. Untuk kegiatan pengolahan, PT Trakindo Utama memiliki pilihan unit yang terbaik menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Penumpukan / Pemuatan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan kemudian ditumpuk di TPN (tempat penimbunan kayu). Log kemudian dimuat ke truk untuk pengiriman ke tempat penimbunan pabrik atau kadang-kadang langsung diumpankan ke tempat pengumpan. Kami menyediakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Randall Rotating Grapple, atau Fixed Grapple untuk aplikasi penyusunan atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill Yard</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan pabrik pulp dapat beroperasi terus menerus. Cat 320DFM untuk operasi di Mill Yard merupakan pilihan terbaik.
                      </div>
                    </div>
                  </div>
                  <div v-bind:class="{'hidden': openTab !== 3, 'block': openTab === 3}">
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">1. Infrastruktur</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Sebelum pengambilan pohon dari daerah penanaman, hal pertama yang harus dibangun adalah akses jalan, kanal, tempat tinggal untuk pekerja dan bengkel untuk peralatan dan alat-alat pemeliharaan. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan persiapan infrastruktur menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader (120K), and Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Pemanenan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji, felling head, atau harvester head. Kayu log kemudian dibersihkan dari cabang-cabangnya dengan menggunakan parang, gergaji, atau harvester head. Setelah ditebang, kontraktor akan menyediakan debarked log jika diminta oleh pembeli. Log kemudian dipotong dengan panjang standar tertentu. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan pemanenan menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Ekstraksi</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN (tempat penimbunan kayu) selain hauling road menggunakan perahu, skidder, forwarder atau “sampan darat” – modifikasi excavator dengan penyimpanan log di belakang untuk mengekstrak log. PT Trakindo Utama memiliki pilihan unit yang terbaik untuk kegiatan ekstraksi menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Fixed Grapple atau menggunakan Cat Wheel Skidder 525.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Pengolahan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap panen, akan dilakukan debarked dengan menggunakan processing head, atau menggunakan metodologi lain selama diterima oleh pembeli. Hasil dari tahap ini adalah semua log telah memenuhi panjang yang telah ditentukan dan sudah dalam kondisi debarked. Untuk kegiatan pengolahan, PT Trakindo Utama memiliki pilihan unit yang terbaik menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Penumpukan / Pemuatan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan kemudian ditumpuk di TPN (tempat penimbunan kayu). Log kemudian dimuat ke truk untuk pengiriman ke tempat penimbunan pabrik atau kadang-kadang langsung diumpankan ke tempat pengumpan. Kami menyediakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan Randall Rotating Grapple, atau Fixed Grapple untuk aplikasi penyusunan atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Mill Yard</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan pabrik pulp dapat beroperasi terus menerus. Cat 320DFM untuk operasi di Mill Yard merupakan pilihan terbaik.
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
    <div class="container mx-auto lg:mb-12 md:mb-6 mb-3 lg:py-16 md:py-8 py-4 px-8">
      <div class="flex space-x-4 place-content-center">
        <div class="w-3/4 mr-2">
          <h3 class="lg:text-4xl">PEMBIAYAAN</h3>
          <div class="pt-8 mb-8">
            Untuk membantu pelanggan sektor kehutanan dalam membeli alat berat Cat, Trakindo dapat membantu Anda dalam berhubungan dengan berbagai institusi keuangan rekanan kami. Kami akan memastikan bisnis Anda dapat memperoleh solusi pembayaran yang sesuai dengan kebutuhan dan keperluan operasi kehutanan Anda.
          </div>
          <a class="bg-yellow-400 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded" href="#">Cat Financial</a>
        </div>
        <div class="w-3/12">
          <img class="lg:h-64 md:h-56 sm:h-44 h-32 lg:w-64 md:w-56 sm:w-44 w-32" src="https://fajarcorp.com/wp-content/uploads/2021/11/adeolu-eletu-E7RLgUjjazc-unsplash-600x397.jpg" alt="">
        </div>
      </div>
      
    </div>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Angkutan',
  data () {
    return {
      title: 'Angkutan - Fajar Corp',
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
