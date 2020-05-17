<template>
  <div>
    <div id="carouselExampleIndicators" class="carousel slide" data-ride="carousel">
      <div class="carousel-inner">
        <div class="carousel-item active" ref="carouselimg">
          <div
            class="d-block w-100 imgslider"
            style="background-image: url('https://www.spacex.com/sites/spacex/files/demo1_iss2_v2.jpg');"
          ></div>
        </div>
        <div class="carousel-item active" ref="carouselimg">
          <div
            class="d-block w-100 imgslider"
            style="background-image: url('https://www.spacex.com/sites/spacex/files/0000_mars_landing.jpg');"
          ></div>
        </div>
      </div>
      <a
        class="carousel-control-prev"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="prev"
        @click="toglleimg()"
      >
        <span class="carousel-control-prev-icon" aria-hidden="true"></span>
        <span class="sr-only">Previous</span>
      </a>
      <a
        class="carousel-control-next"
        href="#carouselExampleIndicators"
        role="button"
        data-slide="next"
        @click="toglleimg()"
      >
        <span class="carousel-control-next-icon" aria-hidden="true"></span>
        <span class="sr-only">Next</span>
      </a>
    </div>
  </div>
</template>

<script>
export default {
  methods: {
    toglleimg() {
      this.$refs['carouselimg'].classList.toggle('active')
      //   this.$refs['navbar-toggler'].classList.toggle('collapse')
    }
  }
}
</script>



<style scoped>
.imgslider {
  height: 70vh;
  background-size: cover;
  background-position: center center;
}
</style>