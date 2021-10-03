<template>
    <div class="nav">
        <div class="nav-header">
            <NavTextPart color="#F5145B" msg="better" class="bold"/>
            <NavTextPart color="#264653" msg="compile" class="thin"/>
        </div>
        <ul class="nav-menu">
            <li class="nav-menu-li">Blog</li>
            <li class="nav-menu-li">Contact</li>
            <li class="nav-menu-li">Sign in/Sign up</li>
        </ul>
    </div>
</template>

<script setup>
import NavTextPart from './NavTextPart.vue'

</script>
<style scoped lang="sass">
.nav
    height: 15vh
    display: flex
    flex-direction: row
    justify-content: space-between
    align-items: center
    padding: 0 150px
.nav-menu 
    list-style-type: none
    display: flex
.nav-menu-li 
    margin-left: 40px
    color: #264653
    cursor: pointer
    font-weight: 400
    font-size: 1.1rem
.bold
    font-weight: 500
.thin
    font-weight: 300
</style>
