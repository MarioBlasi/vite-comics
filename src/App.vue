<script>
export default {};
</script>
<!-- JS ---------------->

<template>
  <div class="navTop-level">
    <div class="container-top">
      <div class="row-top" id="box">
        <div class="col-8">lorem</div>
        <div class="col-4">
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
          <a class="nav-link" href="">contact</a>
        </div>
      </div>
    </div>
  </div>
  <!-- nav top level -->
  <div class="navMedium-level">
    <div class="container-medium">
      <div class="row-medium" id="boxDue">
        <div class="col">
          <h1>- ->Content goes here -</h1>
        </div>
      </div>
    </div>
  </div>
  <!-- nav medium level -->
  <div class="navBottom-level">
    <div class="container-bottom">
      <div class="row-bottom" id="boxTre">
        <div class="col">
          <div class="product">lorem</div>
        </div>
        <div class="col">
          <div class="product">lorem</div>
        </div>
        <div class="col">
          <div class="product">lorem</div>
        </div>
        <div class="col">
          <div class="product">lorem</div>
        </div>
        <div class="col">
          <div class="product">lorem</div>
        </div>
      </div>
    </div>
  </div>
  <!-- nav bottom level -->

  <main>
    <div class="container">
      <div class="row">
        <div class="col-6">
          <div class="vertical-boxUno text-bg-primary p-3">
            <ul>
              <li><h3>testo</h3></li>
              <li>1</li>
              <li>1</li>
              <li>1</li>
              <li>1</li>
              <li>1</li>
              <li>1</li>
              <li>1</li>
              <br />
              <li><h3>testo</h3></li>
              <br />
              <li>1</li>
              <li>1</li>
            </ul>
          </div>
          <!-- vertical box 1 -->
        </div>
        <div class="col-6"></div>
      </div>
    </div>
  </main>
  <!-- main -->

  <footer>
    <div class="container">
      <div class="row-bottom">
        <div class="col-6f">
          <button type="button" class="btn btn-primary">Primary</button>
        </div>
        <hr />
        <div class="col-6f">
          <div>
            <a href=""> <h3>FOLLOW US</h3> </a>
          </div>
          <div class="social">
            <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
            <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
            <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
            <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
            <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
          </div>
        </div>
      </div>
    </div>
  </footer>
  <!-- footer -->
</template>
<!-- HTML ---------------->

<style lang="scss" scoped>
.navTop-level {
  height: 7rem;
}
#box {
  display: flex;
  justify-content: space-around;
  // height: 8rem;
}
.col-8 {
  background-color: aqua;
}
.col-4 {
  display: flex;
  background-color: aqua;
  a {
    padding: 0.5rem;
  }
}
// nav -----end------top
#boxDue {
  display: flex;
  justify-content: center;
  text-align: center;
}
.navMedium-level {
  background-color: rgb(208, 235, 183);
  height: 7rem;
}
// nav -----end------medium
.navBottom-level {
  height: 7rem;
  background-color: rgb(202, 154, 184);
}
#boxTre {
  display: flex;
  justify-content: space-around;
  text-align: center;
  .product {
    padding: 0.5rem 1rem;
  }
}
// // nav -----end------bottom
main {
  background-color: rgb(81, 177, 62);
}
// Main---------
footer {
  background-color: rgba(7, 115, 134, 0.466);
  display: flex;
  justify-content: center;
  height: 7rem;
}

.row-bottom {
  display: flex;
  flex-direction: row;
}
.col-6f {
  background-color: aqua;
  text-align: center;
  display: flex;

  .product {
    padding: 1rem 1rem;
  }
}
</style>
<!-- CSS ----------------->
