<template>
  <div class="footer">
    <ul class="footer-list">
      <li class="footer-list-li-header">Contact</li>
      <li class="footer-list-li-content">- bettercompile on Facebook</li>
      <li class="footer-list-li-content">- contact@bettercompile.us</li>
      <li class="footer-list-li-content">- bettercompile on Twitter</li>
    </ul>
    <ul class="footer-list">
      <li class="footer-list-li-header">Localization</li>
      <li class="footer-list-li-content">- Los Angeles Artor Place 14/A</li>
      <li class="footer-list-li-content">- Oklahoma Bished Street 11/B</li>
      <li class="footer-list-li-content">- New york Baye Street 8</li>
    </ul>
    <ul class="footer-list">
      <li class="footer-list-li-header">Privacy Policy</li>
      <li class="footer-list-li-content">- Statute</li>
      <li class="footer-list-li-content">- License</li>
    </ul>
  </div>
</template>

<script setup>
</script>

<style scoped lang="sass">
.footer
  height: 25vh
  background: #2D2D2D
  display: flex
  justify-content: center
  color: white
  &-list
    margin-top: 50px
    list-style-type: none
    &-li-header
      font-size: 1.5rem
      font-weight: 300
    &-li-content
      font-weight: 300
</style>