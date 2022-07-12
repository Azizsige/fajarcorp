<template>
  <div>
    <Navbar/>
      <div class="bg-gray-100 py-16">
        <div class="contaienr lg:mx-56 md:mx-36 mx-8">
          <div class="flex justify-center items-center">
              <div class="text-center">
                <h2 class="lg:text-4xl md:text-2xl textl-xl font-bold mb-10">VISI KAMI</h2>
                <span class="text-xl mb-10">Menjadi penyedia solusi jasa kelas dunia untuk peralatan Caterpillar.</span>
              </div>
          </div>
          <hr class="bg-black p-0.5 my-10">
          <div class="">
              <h2 class="lg:text-4xl md:text-2xl textl-xl font-bold mb-10">MISI KAMI</h2>
              Membangun perusahaan yang mampu menciptakan lapangan pekerjaan yang layak dan berkualitas bagi sebanyak mungkin rakyat Indonesia, dengan mengusung nilai-nilai berikut:
              <ol class="pl-10 pt-5 list-disc">            
                <li>Layanan dan Produk yang Bisa memberikan solusi</li>
                <li>Menyediakan alat dan teknologi yang Unggul</li>
                <li>Memperlakukan Pelanggan Sebagai Sahabat dan bisa membantu menyelesaikan masalah yg di hadapi customer</li>
                <li>Memuaskan kebutuhan dan harapan konsumen dengan fokus pada kualitas produk dan jasa yg tinggi</li>
              </ol>
          </div>
        </div>
      </div>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'VisiMisi',
  data () {
    return {
      title: 'Visi & Misi - Fajar Corp'
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
