<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Suku Cadang"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'SukuCadang',
  data () {
    return {
      title: 'Suku Cadang - Fajar Corp'
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
