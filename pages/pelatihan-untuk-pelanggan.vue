<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <div class="flex">
          <div class="flex-1">

          </div>
          <div class="flex-1">
            <h3 class="lg:text-3xl">PELATIHAN UNTUK PELANGGAN</h3>
            <div class="pt-8">
             Trakindo berkomitmen untuk terus meningkatkan pengetahuan dan keterampilan para pelanggan dalam pengoperasian dan perawatan alat berat Cat®. Hanya melalui pengoperasian dan perawatan yang sesuai dengan standar Cat, alat berat pelanggan dapat digunakan dengan optimal. Pelatihan-pelatihan ini dibawakan oleh instruktur yang sudah mendapatkan akreditasi dari Caterpillar (CIAP), dimana para instruktur dilengkapi dengan metodologi pengajaran yang standar guna memastikan diperolehnya kompetensi sebagai hasil pembelajaran. Waktu pelaksanaan dapat dilakukan mengikuti jadwal yang sudah tersedia pada halaman situs ini dan dilakukan di fasilitas Training Center Trakindo. Selain itu Trakindo juga dapat menyelenggarakan pelatihan sesuai dengan kebutuhan dan bertempat di lokasi pelanggan.
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
  name: 'PelatihanUntukPelanggan',
  data () {
    return {
      title: 'Pelatihan Untuk Pelanggan - Fajar Corp'
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
