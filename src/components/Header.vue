<template>
  <div>
    <div class="header">
      <div class="logo">
        <img class="logo-img" src="../assets/dc-logo.png" alt="logo-img" />
      </div>
      <div class="nav">
        <ul class="nav-ul">
          <li class="navbar-item"  v-for="(item, index) in navBarItems" :class="index===i ? 'active':''"  :key="index" ><a :href="item.href">{{item.name}}</a> </li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "Header",
  data() {
    return {
      navBarItems: [
        {
          name: "CHARACTERS",
          href: "#characters",
        },
        {
          name: "COMICS",
          href: "#comics",
        },
        {
          name: "MOVES",
          href: "#moves",
        },
        {
          name: "TV",
          href: "#tv",
        },
        {
          name: "GAMES",
          href: "#games",
        },
        {
          name: "COLLECTIBLES",
          href: "#collectibles",
        },
        {
          name: "VIDEOS",
          href: "#videos",
        },
        {
          name: "FANS",
          href: "#fans",
        },
        {
          name: "NEWS",
          href: "#news",
        },
        {
          name: "SHOP",
          href: "#shop",
        },
      ],
      currentActive: 0,
    };
  },
};
</script>

<style lang="scss"></style>
