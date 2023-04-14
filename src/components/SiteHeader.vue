<script>
export default {
  name: "SiteHeader",
  data() {
    return {};
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
            <li class="nav-item">
              <a class="nav-link active" aria-current="page" href="#"
                >CHARACTERS</a
              >
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">COMICS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">MOVIES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">TV</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">GAMES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">COLLECTIBLES</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">VIDEOS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">FANS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">NEWS</a>
            </li>
            <li class="nav-item">
              <a class="nav-link" href="#">SHddddOP</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>
<!-- HTML----------------->
<style lang="scss" scoped></style>
<!-- CSS ----------------->
