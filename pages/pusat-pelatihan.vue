<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <div class="flex">
          <div class="flex-1">

          </div>
          <div class="flex-1">
            <h3 class="lg:text-3xl">PUSAT PELATIHAN TRAKINDO</h3>
            <div class="pt-8">
             Pusat Pelatihan (Training Center) Trakindo merupakan salah satu fasilitas pelatihan terbaik dari semua dealer Caterpillar di dunia. Seiring dengan pertumbuhan bisnis Trakindo, Training Center di Cileungsi ini tetap mempertahankan Caterpillar 5-Star Rating untuk Learning Capabilities Assessment Tools (LCAT) yang auditnya dilaksanakan secara tahunan. <br><br>
             Didirikan tak lama setelah Trakindo berdiri di tahun 1970, Training Center secara berkelanjutan mengembangkan kapasitas dan kapabilitasnya, mulai dari instruktur, fasilitas, workshop, hingga sesi pelatihannya. Ini adalah bagian dari komitmen Trakindo untuk selalu memajukan pengembangan tenaga profesional pelanggan dan perusahaan.
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
  name: 'PusatPelatihan',
  data () {
    return {
      title: 'Pusat Pelatihan - Fajar Corp'
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
