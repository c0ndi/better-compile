<template>
  <div class="section">
    <div class="section-container-row">
      <img src="../assets/photo-8.png" />
      <div class="section-container-row-text-box">
        <div class="row-parts">
          <text-part-vue color="#264653" msg="we " class="thin text-part-vue" />
          <text-part-vue
            color="#F5145B"
            msg="finding "
            class="bold text-part-vue"
          />
          <text-part-vue
            color="#F5145B"
            msg="better "
            class="bold text-part-vue"
          />
          <text-part-vue color="#264653" msg="way" class="thin text-part-vue" />
        </div>
        <span class="row-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis
          saepe eum iusto repellendus nihil, vero voluptatibus deleniti dicta
          neque facilis!
        </span>
      </div>
    </div>
    <div class="section-container-row">
      <div class="section-container-row-text-box">
        <div class="row-parts">
          <text-part-vue
            color="#264653"
            msg="faster"
            class="thin text-part-vue"
          />
          <text-part-vue
            color="#F5145B"
            msg="than"
            class="bold text-part-vue"
          />
          <text-part-vue
            color="#264653"
            msg="everyone"
            class="thin text-part-vue"
          />
        </div>
        <span class="row-text">
          Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis
          saepe eum iusto repellendus nihil, vero voluptatibus deleniti dicta
          neque facilis!
        </span>
      </div>
      <img src="../assets/photo-2.png" />
    </div>
  </div>
</template>

<script setup>
import TextPartVue from "./TextPartVue.vue";
</script>

<style scoped lang="sass">
.section
  display: flex
  flex-direction: column
  height: 100vh
  .section-container-row
    display: flex
    justify-content: space-evenly
    align-items: center
    height: 50%
    .section-container-row-text-box
      width: 20%
      .row-parts
        padding: 20px 0
        .text-part-vue
          font-size: 2rem
        .bold
          font-weight: 600
        .thin
          font-weight: 400
      .row-text
        color: #264653
    img
      width: 450px
      height: 250px
      align-self: center
</style>