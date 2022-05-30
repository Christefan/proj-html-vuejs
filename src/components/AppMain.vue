<template>
  <main>
    <div class="jumbotron">
      <div class="container d-flex align-items-center">
        <div class="row-cols-12 text-center">
          <h1>Contemporary Ideas</h1>
          <p class="py-2">
            Lorem ipsum, dolor sit amet consectetur adipisicing elit. Ullam
            provident a non reprehenderit, repudiandae nobis et saepe tempora
            esse nihil quibusdam dignissimos voluptates consequuntur, assumenda
            corporis atque eius. Eum, non?
          </p>
          <button class="button-c mt-3">REGISTER NOW</button>
        </div>
      </div>
    </div>
    <div class="selection-application">
      <div class="container-fluid">
        <div class="row">
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
          <div class="container-application mx-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
          </div>
        </div>
      </div>
    </div>
  </main>
</template>

<script>
export default {
  name: "AppMain",
};
</script>

<style lang="scss" scoped>
main {
  .jumbotron {
    background-image: url("../assets/img/h5-slide-3-background.jpg");
    .container {
      height: 92vh;
      color: white;
      p {
        font-size: 13px;
      }
      .button-c {
        background-color: #40c4ff;
        border: none;
        color: white;
        padding: 15px 32px;
        text-align: center;
        text-decoration: none;
        display: inline-block;
        font-size: 16px;
      }
    }
  }

  .selection-application {
    background-color: #40c4ff;
    height: 40vh;
    .container-application {
      height: 9vh;
      width: calc(60% / 6);
      background-color: antiquewhite;
    }
  }
}
</style>
