<template>
  <div id="app" class="sans-serif">
    <Header/>
    <Home msg="Tasks Pointing Sessions" class="black-60"/>
    <Footer/>
  </div>
</template>

<script>
import Home from './components/Home.vue'
import Footer from './components/Footer.vue'
import Header from './components/Header.vue'

export default {
  name: 'App',
  components: {
    Home,
    Footer,
    Header
  }
}
</script>

<style>
@import url(./assets/tachyons.css);
</style>
