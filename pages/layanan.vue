<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Layanan"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Layanan',
  data () {
    return {
      title: 'Layanan - Fajar Corp'
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
