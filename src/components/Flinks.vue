<template>
  <div class="bg-flinks-img">
      <div class="flinks">
        <div class="col-50">
          <div class="col-list">
              <h4>DC COMICS</h4>
              <ul>
                  <li v-for="(item,index) in dccomicsList" :key="index">
                      <a href="">{{item.name}}</a>
                  </li>
              </ul>
              <h4>SHOP</h4>
              <ul>
                  <li v-for="(item,index) in dcshopList" :key="index">
                      <a href="">{{item.name}}</a>
                  </li>
              </ul>
          </div>
          <div class="col-list">
              <h4>DC</h4>
              <ul>
                  <li v-for="(item,index) in dcList" :key="index">
                      <a href="">{{item.name}}</a>
                  </li>
              </ul>
          </div>
          <div class="col-list">
              <h4>SITES</h4>
              <ul>
                  <li v-for="(item,index) in sitesList" :key="index">
                      <a href="">{{item.name}}</a>
                  </li>
              </ul>
          </div>
      </div>
      <div class="col-50 dc-image-col"></div></div>
      
  </div>
</template>

<script>
export default {
  name: "Flinks",
  data() {
    return {
      dccomicsList: [
        {
          name: "Characters",
        },
        {
          name: "Comics",
        },
        {
          name: "Movies",
        },
        {
          name: "TV",
        },
        {
          name: "Games",
        },
        {
          name: "Videos",
        },
        {
          name: "News",
        },
      ],
      dcshopList: [
        {
          name: "Shop DC",
        },
        {
          name: "Shop DC Collectibles",
        },
      ],
      dcList: [
          {
          name: "Terms Of Use",
        },
        {
          name: "Privacy Police (New)",
        },
        {
          name: "Ad Choices",
        },
        {
          name: "Advertising",
        },
        {
          name: "Jobs",
        },
        {
          name: "Subscriptions",
        },
        {
          name: "CPSC Certificates",
        },
        {
          name: "Ratings",
        },
        {
          name: "Shop Help",
        },
        {
          name: "Contact Us",
        },
      ],
      sitesList: [
          {
              name: "DC"
          },
          {
              name: "DC UNIVERSEINFINITE"
          },
          {
              name: "DC Kids"
          },
          {
              name: "DC Shop"
          },
          {
              name: "MAD Magazine"
          },
      ],
    };
  },
};
</script>

<style></style>
