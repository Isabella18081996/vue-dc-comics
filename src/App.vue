<template>
  <div id="app">

    <HeaderComp />
    <JumbotronComp />
    <MainComp />
    <SectionShopComp />
    <FooterComp />


  </div>
</template>

<script>
import FooterComp from './components/FooterComp.vue'
import HeaderComp from './components/HeaderComp.vue'
import JumbotronComp from './components/JumbotronComp.vue'
import MainComp from './components/MainComp.vue'
import SectionShopComp from './components/SectionShopComp.vue'




export default {
  name: 'App',
  components: {
    HeaderComp,
    MainComp,
    FooterComp,
    SectionShopComp,
    JumbotronComp,

  
    
  }
}
</script>

<style lang="scss">

@import './assets/style/general.scss';
</style>
