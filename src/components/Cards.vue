
<template>
  <div class="bg-royal">
    <div class="cards">
      <div class="card"
       v-for="(item, index) in card_list" :key="index">
       <img class="card-img" :src="item.img_pass" :alt="item.img_pass">
       <span>{{item.text}}</span>
      </div>
    </div>
  </div>
</template>


<script>
export default {
    name: "Cards",
    data() {
      return {
        card_list : [
        {
          img_pass : require('@/assets/buy-comics-digital-comics.png'),
          text : "DIGITAL COMICS"
        },
        {
          img_pass : require('@/assets/buy-comics-merchandise.png'),
          text : "DC MERCHANDISE"
        },
        {
          img_pass : require('@/assets/buy-comics-subscriptions.png'),
          text : "SUBSCRIPTION"
        },
        {
          img_pass : require('@/assets/buy-comics-shop-locator.png'),
          text : "COMIC SHOP LOCATOR"
        },
        {
          img_pass : require('@/assets/buy-dc-power-visa.svg'),
          text: "DC POWER VISA"
        },
      ]
      }
    },

};
</script>

<style>

</style>