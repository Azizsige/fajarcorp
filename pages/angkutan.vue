<template>
  <div>
    <Navbar />
    <div class="wrapper text-center pb-5">
      <HeroIndustri id="angkutan" />
      <div class="button">
        <button
          type="submit"
          class="bg-red-500 text-white lg:py-3 py-1 lg:px-6 px-2 lg:rounded-lg rounded"
          href="#"
        >
          Request Quote
        </button>
      </div>
    </div>
    <div class="w-full">
      <div
        class="container flex flex-col space-y-7 xl:space-y-0 xl:flex-row items-center xl:space-x-8 mx-auto lg:py-16 md:py-8 py-4 px-8"
      >
        <div class="img">
          <ClipIndustri
            class="w-[225rem] h-[18rem] xl:h-96"
            src="assets/img/angkutan.jpg"
          />
        </div>
        <div class="content">
          <h3 class="lg:text-4xl font-bold">ANGKUTAN</h3>
          <div class="pt-3 xl:pt-8">
            Indonesia memiliki kekayaan hasil hutan yang luar biasa. Seiring
            dengan perkembangan pengelolaan hutan yang terpadu dan berwawasan
            hijau, ada empat segment utama di dalam pengelolaan manfaat hasil
            hutan di Indonesia, baik itu Hutan Alam ataupun Hutan Tanaman
            Industri. Pada setiap segmen, Trakindo turut berpartisipasi membantu
            usaha di bidang kehutanan untuk menjadi lebih efektif dan efisien,
            dari mulai tahap pembukaan lahan sampai ke dukungan di operasi Mill
            Yard. We are ready to advance your business forward.
          </div>
        </div>
      </div>
    </div>
    <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
      <h3 class="lg:text-4xl font-bold">RANTAI NILAI ANGKUTAN</h3>
      <div class="pt-1">
        Indonesia memiliki kekayaan hasil hutan yang luar biasa. Seiring dengan
        perkembangan pengelolaan hutan yang terpadu dan berwawasan hijau, ada
        empat segment utama di dalam pengelolaan manfaat hasil hutan di
        Indonesia, baik itu Hutan Alam ataupun Hutan Tanaman Industri. Pada
        setiap segmen, Trakindo turut berpartisipasi membantu usaha di bidang
        kehutanan untuk menjadi lebih efektif dan efisien, dari mulai tahap
        pembukaan lahan sampai ke dukungan di operasi Mill Yard. We are ready to
        advance your business forward.
      </div>

      <div class="pt-8">
        <div class="flex flex-wrap">
          <div class="w-full">
            <ul
              class="flex mb-0 list-none flex-wrap space-y-1 xl:space-y-0 flex-row"
            >
              <li
                class="-mb-px last:mr-0 md:flex-1 sm:flex-nowrap text-center cursor-pointer"
              >
                <a
                  id="clip_para"
                  class="md:text-lg text-white sm:text-base border-2 border-[#6eab45] text-sm break-words font-bold px-10 py-3 shadow-lg rounded-md block leading-normal"
                  v-on:click="toggleTabs(1)"
                  v-bind:class="{
                    'text-[#6eab45] bg-white': openTab !== 1,
                    'text-white bg-[#6eab45]': openTab === 1,
                  }"
                >
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
              <li
                class="-mb-px last:mr-0 md:flex-1 sm:flex-nowrap text-center cursor-pointer"
              >
                <a
                  id="clip_para"
                  class="md:text-lg text-white sm:text-base border-[#1ca8e0] border-2 text-sm break-words font-bold px-10 py-3 shadow-lg rounded-md block leading-normal"
                  v-on:click="toggleTabs(2)"
                  v-bind:class="{
                    'text-[#1ca8e0] bg-white': openTab !== 2,
                    'text-white bg-[#1ca8e0]': openTab === 2,
                  }"
                >
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
              <li
                class="-mb-px last:mr-0 md:flex-1 sm:flex-nowrap text-center cursor-pointer"
              >
                <a
                  id="clip_para"
                  class="md:text-lg text-white sm:text-base border-[#f39221] border-2 text-sm break-words font-bold px-10 py-3 shadow-lg rounded-md block leading-normal"
                  v-on:click="toggleTabs(3)"
                  v-bind:class="{
                    'text-[#f39221] bg-white': openTab !== 3,
                    'text-white bg-[#f39221]': openTab === 3,
                  }"
                >
                  Hutan Tanaman Industri - Cut to Length System
                </a>
              </li>
            </ul>
            <div
              class="relative flex flex-row min-w-0 shadow-xl shadow-black break-words bg-white w-full mb-6 border-2 border-green-400"
            >
              <div class="flex-auto">
                <div class="tab-content tab-space">
                  <div
                    class="px-8 py-10"
                    v-bind:class="{
                      hidden: openTab !== 1,
                      block: openTab === 1,
                    }"
                  >
                    <div
                      class="flex-col xl:flex-row items-center flex space-x-0 xl:space-x-5"
                    >
                      <div
                        class="space-y-1 pt-5 xl:pt-0 xl:space-y-3 xl:w-[70%] order-last xl:order-first"
                      >
                        <h3
                          class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3"
                        >
                          1. Infrastruktur
                        </h3>
                        <hr class="bg-black p-0.5" />
                        <p class="lg:text-base text-sm">
                          Sebelum pengambilan pohon dari daerah penanaman, hal
                          pertama yang harus dibangun adalah akses jalan, kanal,
                          tempat tinggal untuk pekerja dan bengkel untuk
                          peralatan dan alat-alat pemeliharaan. PT Trakindo
                          Utama memiliki pilihan alat berat terbaik untuk
                          kegiatan persiapan infrastruktur menggunakan Cat
                          Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type
                          Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader
                          (120K), and Cat Vibratory Soil Compactor (CS-533).
                        </p>
                      </div>
                      <div class="infra-img">
                        <img
                          class="xl:h-[20rem] h-[15rem]"
                          src="assets/img/insfrastuktur.jpg"
                        />
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        2. Pemanenan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji,
                        felling head, atau harvester head. Kayu log kemudian
                        dibersihkan dari cabang-cabangnya dengan menggunakan
                        parang, gergaji, atau harvester head. Setelah ditebang,
                        kontraktor akan menyediakan debarked log jika diminta
                        oleh pembeli. Log kemudian dipotong dengan panjang
                        standar tertentu. PT Trakindo Utama memiliki pilihan
                        alat berat terbaik untuk kegiatan pemanenan menggunakan
                        Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591
                        LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        3. Ekstraksi
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN
                        (tempat penimbunan kayu) selain hauling road menggunakan
                        perahu, skidder, forwarder atau “sampan darat” –
                        modifikasi excavator dengan penyimpanan log di belakang
                        untuk mengekstrak log. PT Trakindo Utama memiliki
                        pilihan unit yang terbaik untuk kegiatan ekstraksi
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan Fixed Grapple atau menggunakan Cat Wheel Skidder
                        525.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        4. Pengolahan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap
                        panen, akan dilakukan debarked dengan menggunakan
                        processing head, atau menggunakan metodologi lain selama
                        diterima oleh pembeli. Hasil dari tahap ini adalah semua
                        log telah memenuhi panjang yang telah ditentukan dan
                        sudah dalam kondisi debarked. Untuk kegiatan pengolahan,
                        PT Trakindo Utama memiliki pilihan unit yang terbaik
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        5. Penumpukan / Pemuatan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan
                        kemudian ditumpuk di TPN (tempat penimbunan kayu). Log
                        kemudian dimuat ke truk untuk pengiriman ke tempat
                        penimbunan pabrik atau kadang-kadang langsung diumpankan
                        ke tempat pengumpan. Kami menyediakan Cat Hydraulic
                        Excavator (320D2, 313D2 LGP) dengan Randall Rotating
                        Grapple, atau Fixed Grapple untuk aplikasi penyusunan
                        atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        6. Mill Yard
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan
                        pabrik pulp dapat beroperasi terus menerus. Cat 320DFM
                        untuk operasi di Mill Yard merupakan pilihan terbaik.
                      </div>
                    </div>
                  </div>
                  <div
                    class="px-8 py-10"
                    v-bind:class="{
                      hidden: openTab !== 2,
                      block: openTab === 2,
                    }"
                  >
                    <div
                      class="flex-col xl:flex-row items-center flex space-x-0 xl:space-x-5"
                    >
                      <div
                        class="space-y-1 pt-5 xl:pt-0 xl:space-y-3 xl:w-[70%] order-last xl:order-first"
                      >
                        <h3
                          class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3"
                        >
                          1. Infrastruktur
                        </h3>
                        <hr class="bg-black p-0.5" />
                        <p class="lg:text-base text-sm">
                          Sebelum pengambilan pohon dari daerah penanaman, hal
                          pertama yang harus dibangun adalah akses jalan, kanal,
                          tempat tinggal untuk pekerja dan bengkel untuk
                          peralatan dan alat-alat pemeliharaan. PT Trakindo
                          Utama memiliki pilihan alat berat terbaik untuk
                          kegiatan persiapan infrastruktur menggunakan Cat
                          Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type
                          Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader
                          (120K), and Cat Vibratory Soil Compactor (CS-533).
                        </p>
                      </div>
                      <div class="infra-img">
                        <img
                          class="xl:h-[20rem] h-[15rem]"
                          src="assets/img/insfrastuktur.jpg"
                        />
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        2. Pemanenan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji,
                        felling head, atau harvester head. Kayu log kemudian
                        dibersihkan dari cabang-cabangnya dengan menggunakan
                        parang, gergaji, atau harvester head. Setelah ditebang,
                        kontraktor akan menyediakan debarked log jika diminta
                        oleh pembeli. Log kemudian dipotong dengan panjang
                        standar tertentu. PT Trakindo Utama memiliki pilihan
                        alat berat terbaik untuk kegiatan pemanenan menggunakan
                        Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591
                        LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        3. Ekstraksi
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN
                        (tempat penimbunan kayu) selain hauling road menggunakan
                        perahu, skidder, forwarder atau “sampan darat” –
                        modifikasi excavator dengan penyimpanan log di belakang
                        untuk mengekstrak log. PT Trakindo Utama memiliki
                        pilihan unit yang terbaik untuk kegiatan ekstraksi
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan Fixed Grapple atau menggunakan Cat Wheel Skidder
                        525.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        4. Pengolahan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap
                        panen, akan dilakukan debarked dengan menggunakan
                        processing head, atau menggunakan metodologi lain selama
                        diterima oleh pembeli. Hasil dari tahap ini adalah semua
                        log telah memenuhi panjang yang telah ditentukan dan
                        sudah dalam kondisi debarked. Untuk kegiatan pengolahan,
                        PT Trakindo Utama memiliki pilihan unit yang terbaik
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        5. Penumpukan / Pemuatan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan
                        kemudian ditumpuk di TPN (tempat penimbunan kayu). Log
                        kemudian dimuat ke truk untuk pengiriman ke tempat
                        penimbunan pabrik atau kadang-kadang langsung diumpankan
                        ke tempat pengumpan. Kami menyediakan Cat Hydraulic
                        Excavator (320D2, 313D2 LGP) dengan Randall Rotating
                        Grapple, atau Fixed Grapple untuk aplikasi penyusunan
                        atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        6. Mill Yard
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan
                        pabrik pulp dapat beroperasi terus menerus. Cat 320DFM
                        untuk operasi di Mill Yard merupakan pilihan terbaik.
                      </div>
                    </div>
                  </div>
                  <div
                    class="px-8 py-10"
                    v-bind:class="{
                      hidden: openTab !== 3,
                      block: openTab === 3,
                    }"
                  >
                    <div
                      class="flex-col xl:flex-row items-center flex space-x-0 xl:space-x-5"
                    >
                      <div
                        class="space-y-1 pt-5 xl:pt-0 xl:space-y-3 xl:w-[70%] order-last xl:order-first"
                      >
                        <h3
                          class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3"
                        >
                          1. Infrastruktur
                        </h3>
                        <hr class="bg-black p-0.5" />
                        <p class="lg:text-base text-sm">
                          Sebelum pengambilan pohon dari daerah penanaman, hal
                          pertama yang harus dibangun adalah akses jalan, kanal,
                          tempat tinggal untuk pekerja dan bengkel untuk
                          peralatan dan alat-alat pemeliharaan. PT Trakindo
                          Utama memiliki pilihan alat berat terbaik untuk
                          kegiatan persiapan infrastruktur menggunakan Cat
                          Hydraulic Excavator (320D2, 313D2 LGP), Cat Track Type
                          Tractors / Dozer (D5R XL, D6R XL), Cat Motor Grader
                          (120K), and Cat Vibratory Soil Compactor (CS-533).
                        </p>
                      </div>
                      <div class="infra-img">
                        <img
                          class="xl:h-[20rem] h-[15rem]"
                          src="assets/img/insfrastuktur.jpg"
                        />
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        2. Pemanenan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Pada tahap ini, pohon ditebang menggunakan gergaji,
                        felling head, atau harvester head. Kayu log kemudian
                        dibersihkan dari cabang-cabangnya dengan menggunakan
                        parang, gergaji, atau harvester head. Setelah ditebang,
                        kontraktor akan menyediakan debarked log jika diminta
                        oleh pembeli. Log kemudian dipotong dengan panjang
                        standar tertentu. PT Trakindo Utama memiliki pilihan
                        alat berat terbaik untuk kegiatan pemanenan menggunakan
                        Cat Hydraulic Excavator (320D2, 313D2 LGP) dengan SP 591
                        LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        3. Ekstraksi
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Setelah dipanen, log ditumpuk dan diekstraksi ke TPN
                        (tempat penimbunan kayu) selain hauling road menggunakan
                        perahu, skidder, forwarder atau “sampan darat” –
                        modifikasi excavator dengan penyimpanan log di belakang
                        untuk mengekstrak log. PT Trakindo Utama memiliki
                        pilihan unit yang terbaik untuk kegiatan ekstraksi
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan Fixed Grapple atau menggunakan Cat Wheel Skidder
                        525.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        4. Pengolahan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Dalam tahap ini, log yang belum debarked pada tahap
                        panen, akan dilakukan debarked dengan menggunakan
                        processing head, atau menggunakan metodologi lain selama
                        diterima oleh pembeli. Hasil dari tahap ini adalah semua
                        log telah memenuhi panjang yang telah ditentukan dan
                        sudah dalam kondisi debarked. Untuk kegiatan pengolahan,
                        PT Trakindo Utama memiliki pilihan unit yang terbaik
                        menggunakan Cat Hydraulic Excavator (320D2, 313D2 LGP)
                        dengan SP 591 LX Harvester Head.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        5. Penumpukan / Pemuatan
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Log yang diterima dari pengolahan atau pemanenan
                        kemudian ditumpuk di TPN (tempat penimbunan kayu). Log
                        kemudian dimuat ke truk untuk pengiriman ke tempat
                        penimbunan pabrik atau kadang-kadang langsung diumpankan
                        ke tempat pengumpan. Kami menyediakan Cat Hydraulic
                        Excavator (320D2, 313D2 LGP) dengan Randall Rotating
                        Grapple, atau Fixed Grapple untuk aplikasi penyusunan
                        atau pemuatan bertingkat.
                      </div>
                    </div>
                    <div>
                      <h3
                        class="lg:text-xl md:text-lg sm:text-base text-sm font-bold p-3 py-6"
                      >
                        6. Mill Yard
                      </h3>
                      <hr class="bg-black p-0.5" />
                      <div class="lg:text-base text-sm pt-4">
                        Di lokasi Mill Yard, log ditumpuk untuk memastikan
                        pabrik pulp dapat beroperasi terus menerus. Cat 320DFM
                        untuk operasi di Mill Yard merupakan pilihan terbaik.
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
    <div id="footer">
      <div class="wrap container mx-auto lg:py-32 md:py-8 py-6 px-4">
        <div class="flex space-x-4 text-center place-content-center">
          <div class="w-3/4 mr-2">
            <h3 class="text-white font-bold lg:font-normal lg:text-4xl">
              PEMBIAYAAN
            </h3>
            <div class="pt-8 mb-8 text-white">
              Untuk membantu pelanggan sektor kehutanan dalam membeli alat berat
              Cat, Trakindo dapat membantu Anda dalam berhubungan dengan
              berbagai institusi keuangan rekanan kami. Kami akan memastikan
              bisnis Anda dapat memperoleh solusi pembayaran yang sesuai dengan
              kebutuhan dan keperluan operasi kehutanan Anda.
            </div>
            <a
              class="bg-red-500 text-white lg:py-3 lg:px-6 px-2 py-2 lg:rounded-lg rounded"
              href="#"
              >Chat Financial</a
            >
          </div>
        </div>
      </div>
    </div>
    <Footer />
  </div>
</template>

<script>
export default {
  name: "Angkutan",
  data() {
    return {
      title: "Angkutan - Fajar Corp",
      openTab: 1,
    };
  },
  head() {
    return {
      title: this.title,
      meta: [
        {
          hid: "description",
          name: "description",
          content:
            "Fajar Corp - Melayani Dengan Teknologi, Mutu, dan Harga Terbaik",
        },
      ],
    };
  },
  methods: {
    toggleTabs: function (tabNumber) {
      this.openTab = tabNumber;
    },
  },
};
</script>
