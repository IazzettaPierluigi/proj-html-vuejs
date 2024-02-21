<script>
//import dello store
import { store } from "../../store"

//import di mainbox-1
import MainBox1 from "./main-components/MainBox1.vue"

//import di mainbox-2
import MainBox2 from "./main-components/MainBox2.vue";

//import di mainbox-3
import MainBox3 from "./main-components/MainBox3.vue";

//import di mainbox-3
import MainBox4 from "./main-components/MainBox4.vue";

//import di mainbox-3
import MainBox5 from "./main-components/MainBox5.vue";

export default {
    name: "AppMain",

    components: {
        MainBox1,
        MainBox2,
        MainBox3,
        MainBox4,
        MainBox5,
    },

    data() {
        return {
            store
        };
    },
    methods: {

    }
};
</script>

<template>
    <main>

        <MainBox1></MainBox1>

        <MainBox2></MainBox2>

        <MainBox3 :propsElement="store.playlistCards"></MainBox3>

        <MainBox4></MainBox4>

        <MainBox5 :eventsProp="store.eventsArray"></MainBox5>
    </main>
</template>

<style lang="scss" scoped>
@use "../../styles/partials/variables" as *;
@use "../../styles/partials/mixins" as *;

main {
    background-color: black;
    padding-inline: 10px;
}
</style>
