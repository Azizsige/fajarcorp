<template>
  <div>
    <Navbar/>
    <div class="container mx-auto lg:mb-32 md:mb-16 mb-8 px-8">
      <h2 class="lg:text-6xl text-yellow-400 font-bold lg:mb-64 md:mb-32 sm:mb-16 mb-8">PERTANIAN/PERKEBUNAN</h2>
      <a class="bg-yellow-400 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded" href="#">Request Quote</a>
    </div>
    <div class="bg-gray-300">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <h3 class="lg:text-4xl font-bold">PERTANIAN</h3>
        <div class="pt-8">
          Indonesia merupakan negara agraris yang memiliki kekayaan alam luar biasa. Di dalam pemanfaat berbagai segmen agraria seperti perkebunan, pertanian, peternakan, dan pemanfaatan hasil air, Trakindo berkomitmen untuk menyediakan solusi lengkap yang efisien dan efektif, mulai dari tahap persiapan lahan, penanaman sampai perawatan. We are ready to advance your agribusiness forward.
        </div>
      </div>
    </div>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-4xl font-bold">RANTAI NILAI PERTANIAN &amp; PERKEBUNAN</h3>
      <div class="pt-8">
        Rantai nilai Pertanian dan Perkebunan menjelaskan kegiatan utama dan aktifitas pendukung dalam industri pertanian dan perkebunan untuk memberikan produk atau layanan ke pasar. Rantai nilai ini akan membantu Anda memilih  alat berat Cat® yang tepat untuk kebutuhan bisnis Anda
      </div>
      <div class="pt-8">
        <div class="flex flex-wrap border-2 border-yellow-400">
          <div class="w-full">
            <ul class="flex mb-0 list-none pb-4 flex-wrap flex-row">
              <li class="-mb-px mr-2 last:mr-0 md:flex-1 sm:flex-nowrap text-center">
                <a class="lg:text-xl md:text-lg sm:text-base text-sm break-words font-bold px-5 py-3 shadow-lg rounded block leading-normal" v-on:click="toggleTabs(1)" v-bind:class="{'text-black bg-yellow-400': openTab !== 1, 'text-black bg-white': openTab === 1}">
                  Industri Kelapa Sawit
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
                        Untuk membuka area baru kelapa sawit, hal pertama yang harus dibangun adalah akses jalan dan kanal mengacu pada desain perkebunan. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan persiapan infrastruktur menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader (120K), dan Cat Vibratory Soil Compactor (CS-533).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">2. Persiapan Lahan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji, felling head, atau harvester head. Kayu log kemudian dibersihkan dari cabang-cabangnya dengan menggunakan parang, gergaji, atau harvester head. Setelah ditebang, kontraktor akan menyediakan debarked log jika diminta oleh pembeli. Log kemudian dipotong dengan panjang standar tertentu. PT Trakindo Utama memiliki pilihan alat berat terbaik untuk kegiatan pemanenan menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">3. Penanaman</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        <div class="flex">
                          <div class="w-3/4 mr-2">
                            <h5 class="font-bold">3.a. Penanaman Baru</h5>
                            Setelah lahan siap seperti yang direncanakan, tahap selanjutnya adalah penanaman bibit kelapa sawit. Kegiatan ini dapat dilakukan secara manual penuh atau semi-otomatis. PT Trakindo Utama memiliki pilihan terbaik untuk penanaman semi-otomatis menggunakan Cat Mini Hydraulic Excavator (305,5) dikombinasikan dengan Cat Auger.
                          </div>
                          <div class="w-3/12">
                            <img class="lg:h-36 md:h-32 h-28 lg:w-36 md:w-32 w-28" src="https://www.trakindo.co.id/sites/default/files/inline-images/energy-img1.jpg" alt="">
                          </div>
                        </div>
                        <div class="flex">
                          <div class="w-3/4 mr-2">
                            <h5 class="font-bold">3.b. Penananman Kembali</h5>
                            Pada blok yang sudah ditanami pohon kelapa sawit, pohon yang ada harus ditebang terlebih dahulu, dan tunggul kemudian dikelupas. Setelah proses tersebut selesai, penanaman baru dapat dilakukan dengan menggunakan manual penuh atau semi-otomatis. Pada tahap ini, kami memberikan pilihan terbaik untuk pohon kelapa sawit feeling dan chipping menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP) dilengkapi dengan Chipping bucket.
                          </div>
                          <div class="w-3/12">
                            
                          </div>
                        </div>
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">4. Pemeliharaan</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Jalan di perkebunan Kelapa Sawit dibangun untuk menjadi fasilitas pengangkutan utama dalam pemanenan tandan buah segar (Fress Fruit Bunches – FFB). FFB harus sesegera mungkin dikirim ke pabrik untuk diproses lebih lanjut. Untuk memastikan pengangkutan bisa dilakukan dengan lancar, konstruksi jalan harus dipelihara secara terus menerus. Di samping jalan, kanal juga perlu dipelihara secara teratur sebagai rute transportasi, aliran irigasi, dan aliran drainase. PT Trakindo Utama memiliki alat berat pilihan terbaik untuk pemeliharaan Infrastruktur kelapa sawit menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP, 305,5), Cat Track Type Tractors (D3K XL), dan Cat Backhoe Loader (416F).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">5. Mill</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Tandan Buah Segar (Fress Fruit Bunches – FFB) yang diterima di pabrik akan dipilah pilah di loading ramp untuk memastikan standar mutu FFB terpenuhi. Setelah itu, melalui beberapa perlakuan khusus, FFB akan diperas untuk mengekstrak kandungan minyaknya. Limbah dari proses ini dapat digunakan lagi sebagai bahan bakar biomassa, bahan organik yang berkaitan, atau sebagai bahan untuk produk yang berbeda. Kami memiliki alat berat pilihan terbaik untuk Pabrik Kelapa Sawit dan Pengolahan Limbah menggunakan Cat Wheel Loader 924K, Cat Backhoe Loader 416F, Cat Skid Steer Loader 226B2, Cat Diesel Generator set C Series (C13, C15, dan C18), dan pemanfaatan POME menggunakan Cat Gas Generator set CG Series (CG170, CG132).
                      </div>
                    </div>
                    <div>
                      <h3 class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6">6. Energi Listrik dari POME.</h3>
                      <hr class="bg-black p-0.5">
                      <div class="lg:text-base text-sm pt-4">
                        Gas metana yang dihasilkan dari POME (Palm Oil Mill Effluent) oleh bakteri anaerob yang ada di kolam adalah gas yang paling berbahaya bagi lingkungan. Biasanya pabrik kelapa sawit membangun banyak kolam untuk pengolahan POME tanpa mempertimbangkan gas metana yang akan terlepas ke atmosfer, yang pada akhirnya akan menciptakan pemanasan global. Saat ini sudah ada teknologi untuk menangkap gas metana dan mengubahnya menjadi energi melalui aplikasi generator berbahan bakar gas. Caterpillar telah mengumumkan produk Cat CG (MWM diakuisisi pada tahun 2011) untuk aplikasi ini.Produk Cat CG memiliki tiga (3) model yaitu Cat CG132, CG170 dan CG260 dengan rating bervariasi dari 400kW hingga 3.370kW dalam aplikasi biogas. Beberapa perusahaan pertanian telah mengadopsi dan menjalankan teknologi ini untuk mendapatkan sertifikat “Hijau/Ramah lingkungan” bagi produk CPO mereka.
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
  name: 'Kehutanan',
  data () {
    return {
      title: 'Kehutanan - Fajar Corp',
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
