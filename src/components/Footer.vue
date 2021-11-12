<template>
<div class="footer">
  <Dsicons></Dsicons>
  <Flinks></Flinks>
  <Social></Social>
</div>
</template>

<script>
import Dsicons from './Dcicons.vue';
import Flinks from './Flinks.vue';
import Social from './Social.vue';

export default {
  components: { Dsicons, Flinks, Social},
  name: "Footer",
};
</script>

<style></style>
