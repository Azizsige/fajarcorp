<template>
  <div>
    <Navbar/>
    <div class="bg-gray-200">
      <div class="container mx-auto lg:py-16 md:py-8 py-4 px-8">
        <div class="flex">
          <div class="flex-1">

          </div>
          <div class="flex-1">
            <h3 class="lg:text-3xl">MACHINE REBUILD SERVICES</h3>
            <div class="pt-8">
             Trakindo mengoperasikan fasilitas Machine Rebuild Centers berkelas dunia yang menyediakan jasa rebuild alat berat yang tersertifikasi untuk alat berat Cat yang beroperasi di area pertambangan bawah tanah dan open-pit, sehingga memberikan masa kerja kedua untuk alat berat lama anda dengan durasi panjang melebihi alat-alat berat lainnya. Teknisi-teknisi kami yang terlatih untuk rebuild menggunakan peralatan canggih dan melakukan proses yang terkini di bawah standar kontrol keamanan, kualitas dan contamination control yang sama dengan yang digunakan oleh Caterpillar USA. Melalui Machine Rebuild Centers, kami membantu menjaga alat berat Cat anda bekerja dengan biaya per jam yang rendah.
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
  name: 'MachineRebuild',
  data () {
    return {
      title: 'Machine Rebuild - Fajar Corp'
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
