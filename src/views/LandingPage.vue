<script setup>
import navbar from './components/navbar.vue'
import section1 from './components/landingpage/section1-heroimg.vue'
import section2 from './components/landingpage/section2-tripplan.vue'
import section3 from './components/landingpage/section3-choosetrip.vue'
import section4 from './components/landingpage/section4-nextadventure.vue'
import section5 from './components/landingpage/section5-clearprice.vue'
import section6 from './components/landingpage/section6-discoveradventure.vue'
import section7 from './components/landingpage/section7-unforgettabletravel.vue'
import section8 from './components/landingpage/section8-travelblog.vue'

import footers from './components/footer.vue'

</script>

<template>
  <div class="wrapper">
    <navbar />
    <section1 />
    <section2 />
    <section3 />
    <section4 />
    <section5 />
    <section6 />
    <section7 />
    <section8 />
    <footers />
  </div>
</template>

<script setup lang="javascript"></script>

<style>
.wrapper {
  overflow-x: hidden;
  width: 98.7vw;
}
</style>
