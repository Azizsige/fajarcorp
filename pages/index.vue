<template>
  <div>
    <Navbar />
    <div class="flex flex-col xl:flex-row lg:mb-20 md:mb-10 mb-5">
      <div class="w-full xl:w-2/3 lg:mr-7 mr-3">
        <Splide :options="{ rewind: true, autoplay: play }">
          <SplideSlide>
            <img
              class="object-cover w-full clip_right_point"
              src="/assets/img/Trucking.jpeg"
              alt="Trucking"
            />
          </SplideSlide>
          <SplideSlide>
            <img
              class="object-cover w-full clip_right_point"
              src="/assets/img/Graber.jpeg"
              alt="Graber"
            />
          </SplideSlide>
          <SplideSlide>
            <img
              class="object-cover w-full clip_right_point"
              src="/assets/img/traktor.jpeg"
              alt="Traktor"
            />
          </SplideSlide>
          <SplideSlide>
            <img
              class="object-cover w-full clip_right_point"
              src="/assets/img/leaf shredder.jpeg"
              alt="Leaf Shredder"
            />
          </SplideSlide>
          <SplideSlide>
            <img
              class="object-cover w-full clip_right_point"
              src="/assets/img/Harvester.jpeg"
              alt="Harvester"
            />
          </SplideSlide>
        </Splide>
      </div>
      <div class="w-full xl:w-1/3 mt-5 xl:mt-0 grid place-items-center">
        <div>
          <h3
            class="lg:text-6xl md:text-3xl xl:text-left text-center text-xl font-bold text-black mb-3"
          >
            Fajar Group
          </h3>
          <h5 class="sm:text-sm text-xs">
            Melayani dengan Teknologi, Mutu, dan Harga Terbaik
          </h5>
          <div class="flex justify-center items-center lg:mt-12 md:mt-6 mt-3">
            <a
              href="#"
              class="bg-yellow-500 lg:text-xl md:text-lg text-sm lg:p-3 md:p-2.5 p-2 rounded-lg text-white"
              >Learn More</a
            >
          </div>
        </div>
      </div>
    </div>
    <div
      class="flex flex-row mt-10 mb-10 px-5 xl:px-0 space-x-5 lg:space-y-0 lg:flex-row place-content-center lg:space-x-7 lg:mb-32 md:mb-16"
    >
      <a href="#"
        ><IconObject
          tag="IC<br>ON"
          label="UPDATE"
          src="/assets/img/update.jpeg"
      /></a>
      <a href="#"
        ><IconObject
          tag="IC<br>ON"
          label="UPDATE"
          src="/assets/img/product.jpeg"
      /></a>
      <a href="#"
        ><IconObject
          tag="IC<br>ON"
          label="UPDATE"
          src="/assets/img/contact.jpeg"
      /></a>
      <!-- <a href="">
        <img src="/assets/img/product.jpeg" alt="" srcset="" />
      </a> -->
      <!-- <a href="#"
        ><IconObject tag="IC<br>ON" label="PRODUCT" color="product"
      /></a>
      <a href="#"
        ><IconObject tag="IC<br>ON" label="CONTACT" color="contact"
      /></a> -->
    </div>
    <div
      class="flex flex-col space-y-5 xl:space-y-0 xl:flex-row xl:items-center lg:mb-24 md:mb-12 mb-6 lg:px-32 md:px-16 px-8"
    >
      <div class="flex-1 lg:mr-12 md:mr-6 mr-3">
        <ClipPara src="/assets/img/Trucking.jpeg" />
      </div>
      <div class="flex-1 text-left xl:text-right">
        <div class="space-y-3 xl:space-y-7">
          <h3 class="lg:text-7xl md:text-3xl text-xl font-bold text-black">
            Sufa 3 in 1 :
          </h3>
          <h5 class="lg:mt-8 md:mt-4 mt-2 text-sm text-justify tracking-wider">
            Sufa 3 in 1 adalah alat pemupukan dengan 3 kegunaan dalam satu kali
            pengaplikasian nya yaitu : penggemburan tanah serta pengendalian
            gulma, pemupukan dan pembuatan gulud / bumbun untuk menutup hasil
            pengaplikasian pupuk dengan tanah . Dimana terjadi penghematan biaya
            dan waktu dalam pengolahan tanah yg dilakukan .
          </h5>
          <div class="lg:mt-12 md:mt-6 mt-5">
            <a
              href="#"
              class="bg-yellow-500 lg:text-xl md:text-lg text-sm lg:p-3 md:p-2.5 p-2 rounded-lg text-white"
              >Learn More</a
            >
          </div>
        </div>
      </div>
    </div>
    <div
      class="flex flex-col space-y-5 xl:space-y-0 xl:items-center xl:flex-row lg:mb-24 md:mb-12 mb-6 lg:px-32 md:px-16 px-8"
    >
      <div
        class="lg:mr-12 text-left mt-5 xl:text-right md:mr-6 mr-3 flex-1 order-2 xl:order-1"
      >
        <div class="space-y-3 xl:space-y-7">
          <h3 class="lg:text-6xl md:text-3xl text-xl font-bold text-black">
            Agriculture Drone :
          </h3>
          <h5 class="lg:mt-8 md:mt-4 mt-2 text-sm text-justify tracking-wider">
            Drone tanpa awak dengan kapasitas 5 liter , 10 liter , 15 liter , 20
            liter dan 50 liter yang dapat dipergunakan untuk aplikasi
            penyemprotan herbisida ( mengatasi gulma) , aplikasi penyemprotan
            percepatan titik tumbuh tanaman tebu , dan aplikasi penyemprotan
            percepatan tingkat kemasakan tanaman tebu sebelum panen.
            Agricultural Drone mempunyai banyak kegunaan yg dapat membantu
            meningkatkan produksi tanaman dan efisiensi pengolahan tanaman .
          </h5>
          <div class="lg:mt-12 md:mt-6 mt-3">
            <a
              href="#"
              class="bg-yellow-500 lg:text-xl md:text-lg text-sm lg:p-3 md:p-2.5 p-2 rounded-lg text-white"
              >Learn More</a
            >
          </div>
        </div>
      </div>
      <div class="flex-1 order-1 xl:order-2">
        <ClipPara src="/assets/img/drone.jpg" />
      </div>
    </div>
    <div
      class="flex flex-col space-y-5 xl:items-center xl:space-y-0 xl:flex-row lg:mb-24 md:mb-12 mb-6 lg:px-32 md:px-16 px-8"
    >
      <div class="flex-1">
        <ClipPara src="/assets/img/Graber.jpeg" />
      </div>
      <div class="lg:mr-12 md:mr-6 mr-3 flex-1 text-left xl:text-right">
        <div class="space-y-3 xl:space-y-7">
          <h3 class="lg:text-6xl md:text-3xl text-xl font-bold text-black">
            Cane Grabber :
          </h3>
          <h5 class="lg:mt-8 md:mt-4 mt-2 text-sm text-justify tracking-wider">
            Cane graber tersedia dengan beberapa kapasitas power yaitu : 97 HP ,
            110 HP , 155 HP . Dengan panjang daya jangkau lengan graber yg
            berbeda . Cane grabber adalah alat untuk mengumpulkan , mengangkat
            dan memindahkan batang tebu yang telah dipanen dengan bergerak
            menuju ke truk serta meletakkan tebu dalam cengkeraman graber di
            dalam truk .
          </h5>
          <div class="lg:mt-12 md:mt-6 mt-3">
            <a
              href="#"
              class="bg-yellow-500 lg:text-xl md:text-lg text-sm lg:p-3 md:p-2.5 p-2 rounded-lg text-white"
              >Learn More</a
            >
          </div>
        </div>
      </div>
    </div>
    <div
      class="flex flex-col space-y-5 xl:items-center xl:space-y-0 xl:flex-row lg:mb-24 md:mb-12 mb-6 lg:px-32 md:px-16 px-8"
    >
      <div
        class="lg:mr-12 md:mr-6 mr-3 mt-5 xl:mt-0 flex-1 order-2 xl:order-1 text-left xl:text-right"
      >
        <div class="space-y-3 xl:space-y-7">
          <h3 class="lg:text-6xl md:text-3xl text-xl font-bold text-black">
            Sugar cane Leaf Shreder :
          </h3>
          <h5 class="lg:mt-8 md:mt-4 mt-2 text-sm text-justify tracking-wider">
            Sugar cane Leaf shredder tersedia dengan beberapa ukuran dan model
            tergantung kondisi lahan . Sugar cane Leaf shredder adalah alat
            untuk mencacah daun tebu setelah panen tebu sehingga lahan tidak
            perlu lagi di bakar untuk ditanami kembali , Dimana hasil pencacahan
            daun tebu di lahan tersebut bisa digunakan untuk bahan organik
            penambah kesuburan tanah dan menghambat penguapan air untuk lahan
            kering. Sehingga proses pembakaran lahan yg selama ini dilakukan
            (yang beresiko menurunkan kesuburan tanah dan mengakibatkan polusi )
            bisa dihindari .
          </h5>
          <div class="lg:mt-12 md:mt-6 mt-3">
            <a
              href="#"
              class="bg-yellow-500 lg:text-xl md:text-lg text-sm lg:p-3 md:p-2.5 p-2 rounded-lg text-white"
              >Learn More</a
            >
          </div>
        </div>
      </div>
      <div class="flex-1 order-1 xl:order-2">
        <ClipPara src="/assets/img/Cane grabber.jpeg" />
      </div>
    </div>
    <Footer />
  </div>
</template>

<style>
img.clip_right_point {
  -webkit-clip-path: polygon(0 1%, 100% 0%, 75% 100%, 0% 100%);
  clip-path: polygon(0 1%, 100% 0%, 75% 100%, 0% 100%);
}
.splide__slide img {
  height: 80vh !important;
}

@media screen and (min-width: 360px) and (max-width: 1027px) {
  .splide__slide img {
    height: 70vh !important;
  }
}
</style>

<script>
export default {
  name: "Index",
  data() {
    return {
      title: "Fajar Corp - Melayani Dengan Teknologi, Mutu, dan Harga Terbaik",
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
};
</script>
