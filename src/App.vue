<template>
  <navbar class="snap" />
  <first-section class="snap" />
  <second-section class="snap" />
  <Footer class="snap" />
</template>
<script setup>
import Navbar from "./components/Navbar.vue";
import FirstSection from "./components/FirstSection.vue";
import SecondSection from "./components/SecondSection.vue";
import Footer from "./components/Footer.vue";
</script>


<style lang="sass">
*
  font-family: 'Poppins'
  box-sizing: border-box
  scroll-snap-type: y proximity

body
  margin: 0
  padding: 0
.snap
  scroll-snap-align: start
</style>
