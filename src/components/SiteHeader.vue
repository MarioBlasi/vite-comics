<script>
export default {
  name: "SiteHeader",
  data() {
    return {
      menu: [
        {
          text: "Characters",
          href: "#",
          current_page: true,
        },
        {
          text: "Comics",
          href: "#",
          current_page: false,
        },
        {
          text: "Movies",
          href: "#",
          current_page: false,
        },
        {
          text: "Tv",
          href: "#",
          current_page: false,
        },
        {
          text: "Games",
          href: "#",
          current_page: false,
        },
        {
          text: "Collectibles",
          href: "#",
          current_page: false,
        },
        {
          text: "Videos",
          href: "#",
          current_page: false,
        },
        {
          text: "Fans",
          href: "#",
          current_page: false,
        },
        {
          text: "News",
          href: "#",
          current_page: false,
        },
        {
          text: "Shop",
          href: "#",
          current_page: false,
        },
      ],
    };
  },
};
</script>
<!-- JS ---------------->
<template>
  <header>
    <nav
      class="navbar navbar-expand-md navbar-light_nav_color bg-light_nav_color"
    >
      <div class="container">
        <a class="navbar-brand" href="#">
          <img height="70" src="../assets/img/dc-logo.png" alt="" />
        </a>
        <button
          class="navbar-toggler d-lg-none"
          type="button"
          data-bs-toggle="collapse"
          data-bs-target="#main_nav"
          aria-controls="main_nav"
          aria-expanded="false"
          aria-label="Toggle navigation"
        >
          <span class="navbar-toggler-icon"></span>
        </button>
        <div class="collapse navbar-collapse" id="main_nav">
          <ul class="navbar-nav ms-auto mt-2 mt-lg-0">
            <li class="nav-item" v-for="item in menu">
              <a class="nav-link active" :href="item.href">{{ item.text }}</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>
<!-- HTML----------------->
<style lang="scss"></style>
<!-- CSS ----------------->
