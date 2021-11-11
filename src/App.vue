<template>
  <div id="app">
    <Header></Header>
    <Content></Content>
    <Footer></Footer>

  </div>
</template>

<script>
import Header from './components/Header.vue'
import Content from './components/Content.vue'
import Footer from './components/Footer.vue'

export default {
  name: 'App',
  components: {
    Header,
    Content,
    Footer
  }
}
</script>

<style lang="scss">

@import "src/styles/content.scss";
@import "src/styles/header.scss";
@import "src/styles/content.scss";
@import "src/styles/footer.scss";


</style>
