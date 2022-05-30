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
    <div class="selection-application py-5">
      <div class="container-fluid">
        <div class="row text-center text-wrap justify-content-center">
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-1.png" alt="" />
            <h3 class="my-5">Languages</h3>
          </div>
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-2.png" alt="" />
            <h3 class="my-5">Software</h3>
          </div>
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-3.png" alt="" />
            <h3 class="my-5">Business</h3>
          </div>
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-4.png" alt="" />
            <h3 class="my-5">Chemistry</h3>
          </div>
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-5.png" alt="" />
            <h3 class="my-5">Science</h3>
          </div>
          <div class="container-application mx-2 py-5">
            <img src="../assets/img/h5-custom-icon-6.png" alt="" />
            <h3 class="my-5">DIY&Craft</h3>
          </div>
        </div>
      </div>
    </div>
    <section class="list-scroll-image">
      <div class="text px-4">
        <h2 class="fw-bold">The Trusted Name for In-Home Tutoring.</h2>
        <p>
          Lorem ipsum dolor sit, amet consectetur adipisicing elit. Ullam
          possimus ad, cumque, temporibus voluptates, laborum facilis obcaecati
          accusamus rerum eaque eum odio harum quasi neque deleniti nihil
          asperiores exercitationem quae.
        </p>
        <a href="">Learn More</a>
      </div>
      <div class="image">
        <img src="../assets/img/h5-img-1.jpg" alt="" />
        <div class="button-t">
          <p>></p>
          <a href="">TOP</a>
        </div>
      </div>
    </section>
  </main>
</template>

<script>
export default {
  name: "AppMain",
};
</script>

<style lang="scss" scoped>
main {
  a {
    text-decoration: none;
  }
  .jumbotron {
    background-repeat: no-repeat;
    background-size: cover;
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
    height: 50vh;
    .container-application {
      height: 30vh;
      width: calc(90% / 6);
      background-color: #f2f8fc;
    }
  }
  .list-scroll-image {
    height: 80vh;
    // background-color: #40c4ff;
    .text {
      h2 {
        width: 17.7%;
      }
      p {
        font-size: 21px;
      }
    }
  }
  .image {
    img {
      width: 90%;
    }
    .button-t {
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
</style>
