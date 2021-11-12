<template>
<div class="footer">
  <Cards></Cards>
  <Flinks></Flinks>
  <Social></Social>
</div>
</template>

<script>
import Cards from './Cards.vue';
import Flinks from './Flinks.vue';
import Social from './Social.vue';

export default {
  components: { Cards, Flinks, Social},
  name: "Footer",
};
</script>

<style></style>
