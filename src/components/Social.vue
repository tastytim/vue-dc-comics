<template>
  <div class="bg-303030">
    <div class="social_container">
      <button><a href="">SIGN-UP NOW!</a></button>
      <div class="social_row">
        <h5><a href="">FOLLOW US</a></h5>
        <ul>
          <li v-for="(item, index) in socialList" :key="index"><a href=""><img :src="item.imgPass" :alt="item-imgPass"></a></li>
        </ul>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: 'Social',
  data() {
    return {
      socialList:[
        {
          imgPass : require("@/assets/footer-facebook.png"),
        },
        {
          imgPass : require("@/assets/footer-twitter.png"),
        },
        {
          imgPass : require("@/assets/footer-youtube.png"),
        },
        {
          imgPass : require("@/assets/footer-pinterest.png"),
        },
        {
          imgPass : require("@/assets/footer-periscope.png"),
        },
        
        
      ]
    }
  }
}
</script>

<style>

</style>