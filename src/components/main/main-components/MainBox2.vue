<script>


export default {
    name: "MainBox2",

    data() {
        return {

        };
    },
    methods: {

    }
};
</script>

<template>
    <div class="container-fluid p-0  ">
        <div class="text-div text-center d-flex flex-column align-items-center gap-3">
            <h3 class="text-primary text-uppercase fs-5 ">who we are</h3>
            <h1 class="text-white text-uppercase ">sense the jazz</h1>
            <p class="text-secondary w-25 ">Lorem ipsum dolor sit amet consectetur adipisicing elit. Dolores odit deleniti
                distinctio
                quasi voluptate
                dicta itaque, amet quae aliquam facilis soluta voluptatem, iusto, quisquam alias. Qui in magni voluptates
                aliquid.</p>
            <div class="btn text-white  border border-primary px-4 rounded-0   ">read more</div>
        </div>

        <div class="video-container w-100 mt-5 position-relative">
            <img src="../../../assets/Video.jpg" alt="" class="w-100 object-fit-cover ">
            <div class="button-text position-absolute d-flex flex-column align-items-center">

                <button class=" btn border-primary rounded-circle ">
                    <i class="fa-solid fa-play text-primary "></i></button>
                <h1 class="text-white">new music video</h1>
            </div>

        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/mixins" as *;
@use "../../../styles/partials/variables" as *;

.container-fluid {
    margin-top: 200px;

    .text-div {
        margin-top: 300px;
    }

    .video-container {
        .button-text {
            top: 60%;
            left: 50%;
            transform: translate(-50%, -50%);
        }
    }
}
</style>
