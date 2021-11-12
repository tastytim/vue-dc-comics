<template>
  <div class="card">
    <img :src="thumb" alt="" />
    <h3>{{series}}</h3>
  </div>
</template>

<script>
export default {
  name: "Card",
  props:{
      thumb:{
          type: String,
      },
      price:{
          type: String,
      },
      series:{
          type: String,
      },
      type:{
          type: String,
      }
      
  }
};
</script>

<style></style>
