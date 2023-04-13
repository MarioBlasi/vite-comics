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
          <ul>
            <li>1</li>
            <li>2</li>
            <li>3</li>
            <li>4</li>
            <li>5</li>
            <li>6</li>
            <li>7</li>
            <li>8</li>
            <li>9</li>
            <li>10</li>
          </ul>
        </div>
      </div>
    </div>
  </div>
  <!-- nav top level -->
  <div class="navMedium-level">
    <div class="container-medium">
      <div class="row-medium">
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
          <span>sono bottom</span>
          <span>sono bottom</span>
          <span>sono bottom</span>
          <span>sono bottom</span>
          <span>sono bottom</span>
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
          <div class="social">
            <h4>lorem</h4>
            <ul>
              <li>
                <a href="">Instagram <i class="fa fa fa-instagram"></i></a>
              </li>
              <li>
                <a href="">Google <i class="fa fa-google"></i></a>
              </li>
              <li>
                <a href="">Facebook <i class="fa fa-facebook"></i></a>
              </li>
              <li>
                <a href="">Google <i class="fa fa-google"></i></a>
              </li>
              <li>
                <a href="">Facebook <i class="fa fa-facebook"></i></a>
              </li>
            </ul>
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
}
// nav top
.row-medium {
  display: flex;
  justify-content: start;
  height: 8rem;
}
// nav medium
#boxTre {
  display: flex;
  flex-direction: row;
  justify-content: center;
  background-color: rgb(223, 169, 215);
  height: 9rem;
}

//  nav bottom
.navMedium-level {
  background-color: rgb(208, 235, 183);
}
.navBottom-level {
  background-color: rgb(177, 62, 133);
}
// nav * 3
main {
  background-color: rgb(81, 177, 62);
}
footer {
  background-color: rgba(39, 44, 38, 0.466);
  display: flex;
  flex-direction: row;
}
.row-bottom {
  display: flex;
  flex-direction: row;
}
.col-6f {
  background-color: aqua;
}
</style>
<!-- CSS ----------------->
