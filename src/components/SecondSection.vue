<template>
    <div class="section">
        <div class="section-container-row upper">
            <div class="section-container-column left">
                <div class="section-container-text">
                    <div class="section-container-text-content">
                        <text-part-vue msg="we're just " color="#fff" class="text-part-vue" />
                        <text-part-vue msg="better" color="#F5145B" class="text-part-vue" />
                    </div>
                    <div class="section-container-text-content">
                        <text-part-vue msg="create " color="#fff" class="text-part-vue" />
                        <text-part-vue msg="masterpiece " color="#F5145B" class="text-part-vue" />
                        <text-part-vue msg="with new " color="#fff" class="text-part-vue" />
                        <text-part-vue msg="R1" color="#F5145B" class="text-part-vue" />
                    </div>
                </div>
                <div class="section-container-text">
                    <div class="section-container-text-content">
                        <text-part-vue
                            msg="find new speed and make things "
                            color="#fff"
                            class="text-part-vue"
                        />
                        <text-part-vue msg="faster" color="#F5145B" class="text-part-vue" />
                    </div>
                </div>
            </div>
            <div class="section-container-column right">
                <img src="../assets/Applelogo.png" class="photo-cpu" />
            </div>
        </div>
        <!-- Row -->
        <div class="section-container-row lower">
            <img src="../assets/photo-8.png" class="photo-mac" />
            <div class="section-container-row-text-box">
                <div class="row-parts">
                    <text-part-vue color="#264653" msg="we " class="thin text-part-vue" />
                    <text-part-vue color="#F5145B" msg="finding " class="bold text-part-vue" />
                    <text-part-vue color="#F5145B" msg="better " class="bold text-part-vue" />
                    <text-part-vue color="#264653" msg="way" class="thin text-part-vue" />
                </div>
                <span class="row-text">
                    Lorem ipsum dolor sit amet consectetur adipisicing elit. Perferendis
                    saepe eum iusto repellendus nihil, vero voluptatibus deleniti dicta
                    neque facilis!
                </span>
            </div>
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
        width: 100%
        height: 50%
        display: flex
        justify-content: space-evenly
        align-items: center
        .section-container-column
            height: 100%
            display: flex
            flex-direction: column
            justify-content: space-around
            .section-container-text-content
                .text-part-vue
                    font-size: 1.8rem
        .section-container-row-text-box
            width: 20%
            .row-text
                color: #264653
                font-size: 1.25rem
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
    .upper
        background: #000
.photo-cpu 
    height: 45vh
    margin-left: 160px
.photo-mac
    width: 450px
    height: 250px
    align-self: center
</style>