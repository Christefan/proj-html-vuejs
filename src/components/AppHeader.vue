<template>
  <header>
    <nav class="navbar navbar-expand position-absolute">
      <div class="container-fluid py-5 px-5">
        <a class="navbar-brand" href="#">
          <img src="../assets/img/logo-light.png" alt="" />
        </a>
        <div>
          <ul class="navbar-nav">
            <li class="nav-item mx-5">
              <a class="nav-link active" aria-current="page" href="#">HOME</a>
            </li>
            <li class="nav-item mx-5">
              <a class="nav-link" href="#">COURSES</a>
            </li>
            <li class="nav-item mx-5">
              <a class="nav-link" href="#">INSTRUCTORS</a>
            </li>
            <li class="nav-item mx-5">
              <a class="nav-link" href="">EVENTS</a>
            </li>
            <li class="nav-item mx-5">
              <a class="nav-link" href="">PAGES</a>
            </li>
          </ul>
        </div>
      </div>
    </nav>
  </header>
</template>

<script>
export default {
  name: "AppHeader",
};
</script>

<style lang="scss" scoped>
img {
  width: 240px;
  height: 50px;
}
a {
  color: white;
  font-size: 20px;
}
</style>
