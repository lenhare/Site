<template>
  <div id="app">
      <Accessibility/>
      <Header/>
      <Menu/>
      <router-view/>
      <Footer/>
  </div>
</template>

<script>
import Accessibility from '@/components/Accessibility/index.vue'
import Header from '@/components/Header/index.vue'
import Menu from '@/components/Menu/index.vue'
import Footer from '@/components/Footer/index.vue'

export default {
  components: {
    Accessibility,
    Header, 
    Menu,
    Footer
  }
}
</script>


<style lang="scss"></style>
