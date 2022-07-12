<template>
  <div>
    <Navbar/>
    <MenuPage pageTitle="Karier"/>
    <Footer/>
  </div>
</template>

<script>
export default {
  name: 'Karier',
  data () {
    return {
      title: 'Karier - Fajar Corp'
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
