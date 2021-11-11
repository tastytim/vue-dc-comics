<template>
  <div id="app">
    <Header></Header>
    <Content></Content>
    <Footer>
      <Cards></Cards>
    </Footer>
  </div>
</template>

<script>
import Header from "./components/Header.vue";
import Content from "./components/Content.vue";
import Footer from "./components/Footer.vue";
import Cards from "./components/Cards.vue"

export default {
  name: "App",
  components: {
    Header,
    Content,
    Footer,
    Cards,
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
@import "src/styles/cards.scss";


html, body {
  margin: 0px ;
  padding: 0px ;
}

#app {
  font-family: "Mochiy Pop P One", sans-serif;
}
</style>
