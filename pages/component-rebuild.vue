<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <div class="flex">
          <div class="flex-1">
            
          </div>
          <div class="flex-1">
            <h3 class="lg:text-3xl">COMPONENT REBUILD SERVICES</h3>
            <div class="pt-8">
             Trakindo mengoperasikan tiga fasilitas Component Rebuild Center (CRC) berskala besar di wilayah Indonesia, dan fasilitas di Samarinda merupakan CRC pertama yang meraih penghargaan five-star contamination control dari Caterpillar yang kemudian disusul oleh dua fasilitas lainnya. Fasilitas-fasilitas CRC ini dirancang secara unik untuk memastikan waktu perputaran yang cepat, mengurangi biaya rebuild komponen yang tetap berkualitas tinggi dan peningkatan reusability serta kemampuan pengamanan. Dikombinasikan dengan Trakindo Certified Component Program yang memungkinkan pelanggan untuk menukarkan komponennya, CRC Trakindo menyediakan solusi tepat bagi anda untuk menghemat biaya per jam.
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
  name: 'ComponentRebuild',
  data () {
    return {
      title: 'Component Rebuild- Fajar Corp'
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
  }
}
</script>
