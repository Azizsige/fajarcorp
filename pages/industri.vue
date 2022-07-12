<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Industri"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Industri',
  data () {
    return {
      title: 'Industri - Fajar Corp'
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
