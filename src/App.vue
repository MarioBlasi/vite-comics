<script>
import SiteHeader from "./components/SiteHeader.vue";
// import BanneVue from "./components/BannerVue.vue";
// import SiteMain from "./components/SiteMain.vue";
// import SiteFooter from "./components/SiteFooter.vue";
export default {
  components: {
    SiteHeader,

    // SiteMain,
    // SiteFooter,
  },
  data() {
    return {};
  },
};
</script>
<!-- JS ---------------->

<template>
  <SiteHeader></SiteHeader>
  <SiteMain></SiteMain>
  <SiteFooter></SiteFooter>
  <main>
    <div class="container">
      <p>
        Lorem ipsum dolor sit amet consectetur adipisicing elit. Rem aliquam
        commodi! Quia architecto saepe atque? Lorem ipsum dolor sit amet
        consectetur adipisicing elit. Rem aliquam consequuntur harum, deserunt
        quae eos delectus. Quibusdam voluptatum praesentium quis veritatis
        consequatur, voluptates eius quam commodi! Quia architecto saepe atque?
        consectetur adipisicing elit. Rem aliquam consequuntur harum, deserunt
        quae eos delectus. Quibusdam voluptatum praesentium quis veritatis
        consequatur, voluptates eius quam commodi! Quia architecto saepe atque?
      </p>
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

  <footer>
    <div class="top">
      <div class="container">
        <div class="row" id="logo">
          <div class="col-2">
            <div class="item">
              <h4>DC COMICS</h4>
              <ul>
                <li><a href="">drghd</a></li>
                <li><a href="">pasergftadio</a></li>
                <li><a href="">prdrgo wqefrwerdio</a></li>
                <li><a href="">drghd</a></li>
                <li><a href="">drghd</a></li>
              </ul>
            </div>
            <div class="item">
              <h4>SHOP</h4>
              <ul>
                <li><a href="">io</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorelorem</a></li>
              </ul>
            </div>
          </div>
          <div class="col-2">
            <div class="item">
              <h4>DC</h4>
              <ul>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">prwerdio</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorelorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
              </ul>
            </div>
          </div>
          <div class="col-2">
            <div class="item">
              <h4>SITES</h4>
              <ul>
                <li><a href="">lorem</a></li>
                <li><a href="">pqadio</a></li>
                <li><a href="">lorelorem</a></li>
                <li><a href="">lorem</a></li>
                <li><a href="">lorem</a></li>
              </ul>
            </div>
          </div>
          <div class="col">
            <div class="logoDc">
              <img height="450" src="./assets/img/dc-logo-bg.png" alt="" />
            </div>
          </div>
        </div>
      </div>
    </div>
    <!-- top -->
    <div class="bottom">
      <div class="container d-flex justify-content-between">
        <button type="button" class="btn btn-outline">
          <strong>SIGN-UP NOW!</strong>
        </button>

        <div class="social">
          <strong class="follow text-uppercase">Follow us</strong>
          <img src="./assets/img/footer-periscope.png" alt="" />
          <img src="./assets/img/footer-periscope.png" alt="" />
          <img src="./assets/img/footer-youtube.png" alt="" />
          <img src="./assets/img/footer-pinterest.png" alt="" />
          <img src="./assets/img/footer-periscope.png" alt="" />
        </div>
      </div>
    </div>
    <!-- top -->
  </footer>
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
    height: 120px;
    background-color: $blue_nav_color;
    padding: 2rem;
  }
}
// MAIN

footer {
  h4 {
    color: white;
    text-transform: uppercase;
  }
  .top {
    padding: 1rem;
    background-image: url(./assets/img/footer-bg.jpg);

    ul {
      list-style: none;
      padding: 0;
      a {
        color: $light_nav_color;
        text-decoration: none;
      }
    }
  }

  .bottom {
    height: 120px;
    background-color: $grey_footer_color;
    padding: 2rem;
    .social > img {
      padding: 0.3rem;
    }
    .social > .follow {
      padding: 0.8rem;
    }
    .follow {
      color: $blue_nav_color;
      font-size: large;
    }
    .btn {
      border: 3px solid $blue_nav_color;
      height: 3rem;
      width: 10rem;
      background-color: $grey_footer_color;
      color: white;
    }
  }
}
//
</style>
<!-- CSS ----------------->
