<script>


export default {
    name: "MainBox1",

    data() {
        return {
            boxItems: [
                {
                    icon: "(10)",
                    title: "original ideas",

                    paragraph: "Lorem ipsum dolor sitt. Consectetur, voluptate?"
                },
                {

                    icon: "(11)",
                    title: "music studio",

                    paragraph: "Lorem ipsum dolor sit amet consectetur adipisicing elit."
                },
                {
                    icon: "(12)",
                    title: "acoustic covers",

                    paragraph: "Lorem ipsum dolor sit amet consectetur adip."
                }
            ]
        };
    },
    methods: {

    }
};
</script>

<template>
    <div class="container-fluid flex-column align-items-center  d-flex   ">
        <div class="text-box text-white text-center text-uppercase d-flex flex-column align-items-center gap-5 ">
            <h4 class="text-primary mb-2 ">instrumental rock</h4>
            <h1>music in this video</h1>
            <div class="btn text-white  border border-primary px-4 rounded-0   ">read more</div>
        </div>
        <div class="box-container w-100  d-flex flex-row ">

            <div v-for="(element, index) in    boxItems   " :key="index" class="box text-center text-white ">

                <img :src="`../../../src/assets/image${element.icon}.svg`" alt="">

                <h2>{{ element.title }}</h2>

                <p>{{ element.paragraph }}</p>
            </div>
            <!-- <div class="box bg-primary">
                <h1>icon</h1>

                <h2>subtle</h2>

                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eius et dicta nesciunt nihil, deserunt
                    corrupti, enim numquam minus nulla magnam dolorum ea sequi facilis sapiente blanditiis ullam
                    accusantium. Officiis, culpa.</p>
            </div>
            <div class="box bg-primary">
                <h1>icon</h1>

                <h2>subtle</h2>

                <p>Lorem ipsum dolor sit amet consectetur, adipisicing elit. Eius et dicta nesciunt nihil, deserunt
                    corrupti, enim numquam minus nulla magnam dolorum ea sequi facilis sapiente blanditiis ullam
                    accusantium. Officiis, culpa.</p>
            </div> -->
        </div>
    </div>
</template>

<style lang="scss" scoped>
@use "../../../styles/partials/mixins" as *;
@use "../../../styles/partials/variables" as *;

.container-fluid {
    position: relative;
    background-image: url(../../../assets/backgrounds/background1.png);
    background-position: top;
    background-repeat: no-repeat;
    background-size: cover;

    .text-box {
        margin-bottom: 300px;
        margin-top: 200px;

        h4 {
            font-size: 30px;
        }

        h1 {
            font-size: 60px;
        }

    }

    .box-container {
        gap: 20px;
        justify-content: center;
        position: absolute;
        bottom: -25%;

        .box {
            width: calc(50% / 3);
            text-align: center;
            aspect-ratio: 1;
            padding: 40px;
            background-color: #121212;

            img {
                width: 50px;
                height: 20px;
            }

        }
    }
}
</style>
