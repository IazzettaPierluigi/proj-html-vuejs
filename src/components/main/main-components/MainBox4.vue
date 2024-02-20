<script>


export default {
    name: "MainBox4",

    props: [

    ],

    data() {
        return {
            stats: [

                {
                    icon: "(13)",
                    name: "concerts",
                    number: "163"
                },

                {
                    icon: "(14)",
                    name: "happy clients",
                    number: "145"
                },

                {
                    icon: "(15)",
                    name: "music awards",
                    number: "72"
                },

                {
                    icon: "(16)",
                    name: "total songs",
                    number: "182"
                },

            ]
        };
    },
    methods: {

    }
};
</script>

<template>
    <div class="container-fluid  p-0 mt-5 justify-content-center d-flex flex-column align-content-center   ">
        <div class=" album d-flex flex-column gap-2 px-5 align-items-start  text-uppercase d-flex justify-content-center ">
            <h4 class="text-primary">instrumental rock</h4>
            <h1 class="text-white">album out now</h1>
            <div class="btn text-white  border border-primary px-4 rounded-0   ">read more</div>
        </div>

        <div class=" container-fluid stats ">
            <div class="row text-center justify-content-center  ">
                <div v-for="(element, index) in stats" :key="index"
                    class="col-2 text-white p-5 d-flex flex-column align-items-center gap-2 ">
                    <img :src="`../../../src/assets/image ${element.icon}.svg`" alt="">
                    <h1 class="fs-1">{{ element.number }}</h1>
                    <h3 class="text-uppercase fs-4">{{ element.name }}</h3>
                </div>

            </div>
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/mixins" as *;
@use "../../../styles/partials/variables" as *;

.album {
    background-image: url(../../../assets/cms_parallax.jpg);
    background-size: cover;
    background-repeat: no-repeat;
    background-position: center;
    height: 400px;
}

.stats {
    background-image: url(../../../assets/counter_parallax.jpg);

    .row {

        .col-2 {
            img {
                width: 100px;
                height: 100px;
                filter: invert(100%) sepia(0%) saturate(0%) hue-rotate(225deg) brightness(106%) contrast(102%);
            }
        }
    }
}
</style>
