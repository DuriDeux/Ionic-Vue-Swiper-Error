<template>
  <ion-page>
  <swiper
    :effect="'cards'"
    :grabCursor="true"
    :modules="[EffectCards]"
    class="mySwiper"
  >
    <swiper-slide>Slide 1</swiper-slide>
    <swiper-slide>Slide 2</swiper-slide><swiper-slide>Slide 3</swiper-slide>
    <swiper-slide>Slide 4</swiper-slide><swiper-slide>Slide 5</swiper-slide>
    <swiper-slide>Slide 6</swiper-slide><swiper-slide>Slide 7</swiper-slide>
    <swiper-slide>Slide 8</swiper-slide><swiper-slide>Slide 9</swiper-slide>
  </swiper>
</ion-page>
</template>

<script setup>
  import { IonPage, IonHeader, IonToolbar, IonTitle, IonContent } from '@ionic/vue';  // Import Swiper Vue.js components
  import { Swiper, SwiperSlide } from 'swiper/vue';

  // Import Swiper styles
  import 'swiper/css';

  import 'swiper/css/effect-cards';
  // import required modules
  import { EffectCards } from 'swiper';

</script>
