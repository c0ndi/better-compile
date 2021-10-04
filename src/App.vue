<template>
  <Navbar />
  <FirstSection />
  <SecondSection />
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

body
  margin: 0
  padding: 0
</style>
