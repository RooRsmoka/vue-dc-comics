<template>
  <div id="app">
    <header-box/>
    <jumbotron-box/>
    <main-box/>
    <footer-box/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import jumbotronBox from './components/JumbotronBox.vue'
import MainBox from './components/MainBox.vue'
import FooterBox from './components/FooterBox.vue' 


export default {
  name: 'App',
  components: {
    HeaderBox,
    jumbotronBox,
    MainBox,
    FooterBox
  }
}
</script>

<style lang="scss">
@import './style/common.scss';
</style>
