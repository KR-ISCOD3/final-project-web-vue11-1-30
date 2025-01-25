<template>
  <swiper
    :spaceBetween="30"
    :centeredSlides="true"
    :autoplay="{
      delay: 2500,
      disableOnInteraction: false,
    }"
    
    :effect="'fade'"
    :pagination="{
      clickable: true,
    }"
    :navigation="true"
    :modules="modules"
    class="mySwiper rounded-3 overflow-hidden shadow"
  >
    <swiper-slide>
      <div style="height: 70vh" class="bg-secondary rounded-3 overflow-hidden">

        <div class="position-absolute z-3 text-light top-50 start-50 translate-middle text-center">
            <h1 class="text-uppercase">The biggest sale</h1>
            <p class="fs-5">Specail for Today</p>
            <button class="btn bg-pink-700 text-light px-4 fs-6 py-2 text-uppercase">Shop now</button>
        </div>

        <img
          style="filter: brightness(50%)"
          src="https://images.squarespace-cdn.com/content/v1/5c95f8d416b640656eb7765a/1652222190747-TCF6MSHWKSMXHCV5W575/Zenbook+Classic+_+S+_+Pro_UX3402_UP5302_UX7602_UX8402_Scenario+photo_Family+cut.jpg?format=2500w"
          alt=""
          class="w-100 h-100 object-fit-cover"
        />
      </div>
    </swiper-slide>
    <swiper-slide>
      <div style="height: 70vh" class="bg-secondary rounded-3 overflow-hidden">
        <div class="position-absolute z-3 text-light top-50 start-50 translate-middle text-center">
            <h1 class="text-uppercase">The biggest sale</h1>
            <p class="fs-5">Specail for Today</p>
            <button class="btn bg-pink-700 text-light px-4 fs-6 py-2 text-uppercase">Shop now</button>
        </div>
        <img
          style="filter: brightness(50%)"
          src="https://tfgmedia.co.za/wp-content/uploads/2023/03/01-TFG-Tech-05April-FeatureImage.png"
          alt=""
          class="w-100 h-100 object-fit-cover"
        />
        </div>
    </swiper-slide>
    <swiper-slide>
      <div style="height: 70vh" class="bg-secondary rounded-3 overflow-hidden">
        <div class="position-absolute z-3 text-light top-50 start-50 translate-middle text-center">
            <h1 class="text-uppercase">The biggest sale</h1>
            <p class="fs-5">Specail for Today</p>
            <button class="btn bg-pink-700 text-light px-4 fs-6 py-2 text-uppercase">Shop now</button>
        </div>
        <img
          style="filter: brightness(50%)"
          src="https://cdn.thewirecutter.com/wp-content/media/2023/10/instantcameras-2048px-02039.jpg"
          alt=""
          class="w-100 h-100 object-fit-cover"
        />
      </div>
    </swiper-slide>
  </swiper>
</template>
<script setup>
// Import Swiper Vue.js components
import { Swiper, SwiperSlide } from "swiper/vue";

// Import Swiper styles
import "swiper/css/pagination";
import "swiper/css/navigation";
import 'swiper/css/effect-fade';
// import required modules
import { Autoplay, Pagination, Navigation,EffectFade } from "swiper/modules";
import { effect } from "vue";

const modules = [Autoplay, Pagination, Navigation,EffectFade];
</script>
