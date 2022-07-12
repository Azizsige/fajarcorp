<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Pelatihan"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Pelatihan',
  data () {
    return {
      title: 'Pelatihan - Fajar Corp'
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
