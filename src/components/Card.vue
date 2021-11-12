<template>
  <div class="card">
    
      <img class="card-img" :src="thumb" alt="" />
      <div class="card-text">{{ series }}</div>
    
  </div>
</template>

<script>
export default {
  name: "Card",
  props: {
    thumb: {
      type: String,
    },
    price: {
      type: String,
    },
    series: {
      type: String,
    },
    type: {
      type: String,
    },
  },
};
</script>

<style></style>
