<script>


    export default {
        name: "FootSlider",



        data() {
            return {

            };
        },
        methods: {

        }
    };
</script>

<template>
    <div class="p-0 m-0  d-flex w-100  ">
        <figure>
            <img src="../../../assets/instagram_img1.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img2.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img3.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img4.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img5.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img6.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img7.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img8.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img9.jpg" alt="">
        </figure>

        <figure>
            <img src="../../../assets/instagram_img10.jpg" alt="">
        </figure>
    </div>
</template>

<style lang="scss" scoped>
    @use "../../../styles/partials/variables" as *;

    @use "../../../styles/partials/mixins" as *;

    figure {
        width: calc(100% / 10);

        img {
            width: 100%;
        }
    }
</style>