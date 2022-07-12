<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Tentang Kami"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'TentangKami',
  data () {
    return {
      title: 'Tentang Kami - Fajar Corp'
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
