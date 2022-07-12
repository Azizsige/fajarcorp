<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Produk"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Produk',
  data () {
    return {
      title: 'Produk - Fajar Corp'
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
