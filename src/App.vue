<script>
import SiteHeader from "./components/SiteHeader.vue";
import SiteMain from "./components/SiteMain.vue";
export default {
  components: {
    SiteHeader,
    SiteMain,
  },
  data() {
    return {};
  },
};
</script>
<!-- JS ---------------->

<template>
  <!-- 
  <SiteMain></SiteMain>
  <SiteFooter></SiteFooter> -->
  <SiteHeader></SiteHeader>
  <main>
    <div class="container">
      Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem aliquam
      consequuntur harum, deserunt quae eos delectus. Quibusdam voluptatum
      praesentium quis veritatis consequatur, voluptates eius quam commodi! Quia
      architecto saepe atque? Lorem ipsum dolor sit amet consectetur adipisicing
      elit. Rem aliquam consequuntur harum, deserunt quae eos delectus.
      Quibusdam voluptatum praesentium quis veritatis consequatur, voluptates
      eius quam commodi! Quia architecto saepe atque?
    </div>

    <div class="banner">
      <div class="container">
        <div class="row">
          <div class="col">
            <img
              height="50"
              src="./assets/img/buy-comics-digital-comics.png"
              alt=""
            />
            <span class="text-uppercase">Digital Comics</span>
          </div>
          <div class="col">
            <img
              height="50"
              src="./assets/img/buy-comics-merchandise.png"
              alt=""
            />
            <span class="text-uppercase">DC merchandise</span>
          </div>
          <div class="col">
            <img
              height="50"
              src="./assets/img/buy-comics-subscriptions.png"
              alt=""
            />
            <span class="text-uppercase">Subscription</span>
          </div>
          <div class="col">
            <img
              height="50"
              src="./assets/img/buy-comics-shop-locator.png"
              alt=""
            />
            <span class="text-uppercase">comic shop locator</span>
          </div>
          <div class="col">
            <img height="40" src="./assets/img/buy-dc-power-visa.svg" alt="" />
            <span class="text-uppercase">dc power visa</span>
          </div>
        </div>
      </div>
    </div>
  </main>

  <footer></footer>
</template>
<!-- HTML ---------------->

<style lang="scss">
@use "./assets/scss/partials/variables" as *;
@use "./assets/scss/app.scss";

main {
  background-color: $dark_nav_color;
  color: $light_nav_color;
  img,
  span {
    padding: 5px;
  }
  .banner {
    height: 100px;
    background-color: $blue_nav_color;
    padding: 1.5rem;
  }
}
</style>
<!-- CSS ----------------->
