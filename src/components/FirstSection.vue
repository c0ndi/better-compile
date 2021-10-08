<template>
  <div class="section">
    <div class="section-container container-left">
      <img src="../assets/photo-4.svg" class="photo-1" />
      <div class="section-container-content">
        <text-part-vue color="#264653" msg="5" class="section-text-part" />
        <text-part-vue color="#F5145B" msg="times" class="section-text-part" />
        <text-part-vue color="#264653" msg="faster" class="section-text-part last-part" />
        <ul class="section-container-content-list">
          <li class="list-li">
            <text-part-vue color="#F5145B" msg="-" class="section-list-part" />
            <text-part-vue color="#264653" msg="AMD CPU 5.3Ghz 16 cores" class="section-list-part" />
          </li>
          <li class="list-li">
            <text-part-vue color="#F5145B" msg="-" class="section-list-part" />
            <text-part-vue
              color="#264653"
              msg="NVIDIA RTX 2080ti 12GBVRAM"
              class="section-list-part"
            />
          </li>
          <li class="list-li">
            <text-part-vue color="#F5145B" msg="-" class="section-list-part" />
            <text-part-vue color="#264653" msg="1TB NVME STORAGE" class="section-list-part" />
          </li>
          <li class="list-li">
            <text-part-vue color="#F5145B" msg="-" class="section-list-part" />
            <text-part-vue color="#264653" msg="16GB RAM DDR5" class="section-list-part" />
          </li>
        </ul>
      </div>
    </div>
    <div class="section-container container-right">
      <img src="../assets/photo-5.png" class="photo-2" />
    </div>
  </div>
</template>

<script setup>
import TextPartVue from "./TextPartVue.vue";
</script>

<style scoped lang="sass">
.section
  display: flex
  .section-container
    width: 50%
    height: 85vh
  .container-left
    display: flex
    justify-content: center
    align-items: center
    flex-direction: column
    .photo-1
      width: 50%
    .section-text-part
      font-size: 4vw
      font-weight: 200
      .last-part
        margin-right: 12px
    .section-container-content-list
      list-style-type: none
      margin: 0
      padding: 0
      .list-li
        color: #264653
        font-size: 1.2rem
        margin-left: 20px
        .section-list-part
          margin-left: 20px
  .container-right
    display: flex
    justify-content: right
    align-items: center
    .photo-2
      width: 70%
</style>