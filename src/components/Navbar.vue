<template>
  <div class="nav">
    <div class="nav-header">
      <text-part-vue color="#F5145B" msg="better" class="bold nav-text-part" />
      <text-part-vue color="#264653" msg="compile" class="thin nav-text-part" />
    </div>
    <ul class="nav-menu">
      <li class="nav-menu-li">Blog</li>
      <li class="nav-menu-li">Kontakt</li>
      <li class="nav-menu-li">About us</li>
    </ul>
  </div>
</template>
<script setup>
import TextPartVue from "./TextPartVue.vue";
</script>
<style scoped lang="sass">
.nav
  height: 15vh
  display: flex
  flex-direction: row
  justify-content: space-between
  align-items: center
  flex-wrap: wrap
  padding: 0 200px
  .nav-text-part
    font-size: 1.8rem
  .bold
    font-weight: 500
  .thin
    font-weight: 300
.nav-menu
  list-style-type: none
  display: flex
  .nav-menu-li
    margin-left: 40px
    color: #264653
    cursor: pointer
    font-weight: 400
    font-size: 1rem
</style>
