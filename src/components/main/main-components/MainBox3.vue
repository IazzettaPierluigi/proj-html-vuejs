<script>


export default {
    name: "MainBox3",

    props: [
        'propsElement'
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
    <div class="container-fluid p-0  ">
        <div class="row">

        </div>
        <div class="text-div text-center d-flex flex-column align-items-center gap-3">
            <h3 class="text-primary text-uppercase fs-5 ">who we are</h3>
            <h1 class="text-white text-uppercase ">sense the jazz</h1>
        </div>

        <div class="container-cards d-flex  w-100 gap-4 justify-content-center flex-wrap ">
            <div class="row gap-4 w-100 gap-4 justify-content-center flex-wrap ">

                <div v-for="(element, index) in propsElement" :key="index" class="card col-3 p-5 bg-black text-center ">
                    <img :src="element.image" class="card-img-top rounded-0 " :alt="element.title">
                    <div class="card-body">
                        <h4 class="card-title fs-6 text-uppercase text-white">{{ element.title }}</h4>
                    </div>
                </div>
            </div>



        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/mixins" as *;
@use "../../../styles/partials/variables" as *;
</style>
