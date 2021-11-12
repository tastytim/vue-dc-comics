<template>
  <div id="app">
    <Header></Header>
    <Jumbotron></Jumbotron>
    <Content></Content>
    <Footer></Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";
import Jumbotron from "./components/Jumbotron.vue"


export default {
  name: "App",
  components: {
    Header,
    Jumbotron,
    Content,
    Footer,
    
  },
};
</script>

<style lang="scss">


@font-face {
  font-family: "Mochiy Pop P One", sans-serif;
  font-family: "Roboto", sans-serif;
  src: local("Mochiy Pop P One"),
    url(./fonts/MochiyPopPOne-Regular.ttf) format("truetype");
}

@import "src/styles/content.scss";
@import "src/styles/header.scss";
@import "src/styles/content.scss";
@import "src/styles/footer.scss";
@import "src/styles/dsicons.scss";
@import "src/styles/social.scss";
@import "src/styles/flinks.scss";
@import "src/styles/jumbotron.scss";
@import "src/styles/card.scss";


html, body {
  margin: 0px ;
  padding: 0px ;
}

#app {
  font-family: "Mochiy Pop P One", sans-serif;
}
</style>
