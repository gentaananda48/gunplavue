<template>
  <!-- Hero Section Begin -->
  <section class="hero-section">
    <carousel class="hero-items" :items="1" :nav="false" :autoplay="true">
      <div class="single-hero-items set-bg" style="background-image: url('/img/hero-1.png')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>GUNPLA.store</span>
              <h1>Gundam Plastic</h1>
              <p>Toko Gundam Plastic Online #1 di Indonesia</p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg" style="background-image: url('/img/hero-2.png')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>GUNPLA.store</span>
              <h1>Original BANDAI</h1>
              <p>Barang yang kami jual dijamin ORI 100% dari BANDAI</p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
      <div class="single-hero-items set-bg" style="background-image: url('/img/hero-3.png')">
        <div class="container">
          <div class="row">
            <div class="col-lg-5">
              <span>GUNPLA.store</span>
              <h1>Discount 20%</h1>
              <p>Dapatkan Discount terbatas hingga akhir tahun</p>
              <a href="#" class="primary-btn">Shop Now</a>
            </div>
          </div>
        </div>
      </div>
    </carousel>
  </section>
  <!-- Hero Section End -->
</template>

<script>
import carousel from "vue-owl-carousel";

export default {
  name: "HeroShayna",
  components: {
    carousel,
  },
};
</script>
