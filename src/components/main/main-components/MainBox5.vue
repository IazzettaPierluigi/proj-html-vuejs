<script>


export default {
    name: "MainBox5",

    props: [
        'eventsProp'
    ],

    data() {
        return {

        };
    },
    methods: {

    }
};
</script>

<template>
    <div class="container-fluid p-0 mt-5  ">
        <div class="row">

        </div>
        <div class="text-div text-center d-flex flex-column align-items-center gap-3">
            <h3 class="text-primary text-uppercase fs-5 ">who we are</h3>
            <h1 class="text-white text-uppercase ">sense the jazz</h1>
        </div>

        <div class="container-cards d-flex  w-100 gap-4 justify-content-center flex-wrap ">
            <div class="row gap-4 w-100 gap-4 justify-content-center flex-wrap ">

                <div v-for="(element, index) in eventsProp" :key="index" class="card col-3  bg-black ">
                    <img :src="element.image" class="card-img-top rounded-0 " :alt="element.nome">
                    <div class="card-body d-flex flex-column">
                        <h4 class="card-title fs-6 text-uppercase text-white">{{ element.nome }}</h4>
                        <p class="text-primary">{{ element.data }}</p>
                        <p class="text-secondary">{{ element.paragrafo }}</p>

                    </div>
                </div>
            </div>



        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/mixins" as *;
@use "../../../styles/partials/variables" as *;

.card-socials {
    img {
        width: 20px;
        height: 20px;

        filter: invert(100%) sepia(100%) saturate(0%) hue-rotate(288deg) brightness(102%) contrast(102%);
    }

    img:hover {
        filter: invert(58%) sepia(28%) saturate(2491%) hue-rotate(355deg) brightness(97%) contrast(97%);

    }
}
</style>
