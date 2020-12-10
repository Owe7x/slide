<template>
  <div class="container">
    <swiper class="swiper" :options="swiperOption">
      <swiper-slide class="slide-1"><h2>Titile 1</h2></swiper-slide>
      <swiper-slide class="slide-2"><h2>Titile 2</h2></swiper-slide>
      <swiper-slide class="slide-3"><h2>Titile 3</h2></swiper-slide>
      <swiper-slide class="slide-4"><h2>Titile 4</h2></swiper-slide>
      <swiper-slide class="slide-5"><h2>Titile 5</h2></swiper-slide>
  </swiper>
  </div>
</template>

<script>

import { Swiper, SwiperSlide } from 'vue-awesome-swiper';
import 'swiper/swiper-bundle.css';
export default {
    name: 'swiper-example-navigation',
    title: 'Navigation',
    components: {
      Swiper,
      SwiperSlide
    },
    data() {
      return {
        swiperOption: {
          spaceBetween: 30,
          effect: 'fade',
        }
      }
    }
  }
</script>

<style scoped>
.container
  {margin-top: 30px}
.container h1 {
  text-align: center;
}
.container h2 {
  text-align: center;
  color: white;
  padding-top: 15%;
}
.swiper {
  height: 360px;
}
swiper-slide {
  background-position: center;
  background-size: cover;
}
.slide-1 {
  background-image: url("../static/images/1.jpg")
}
.slide-2 {
  background-image: url("../static/images/1.jpg")
}
.slide-3 {
  background-image: url("../static/images/1.jpg")
}
.slide-4 {
  background-image: url("../static/images/1.jpg")
}
.slide-5 {
  background-image: url("../static/images/1.jpg")
}
</style>
