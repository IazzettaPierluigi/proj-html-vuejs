<script>
//import di mainbox-1
import MainBox1 from "./main-components/MainBox1.vue"

//import di mainbox-2
import MainBox2 from "./main-components/MainBox2.vue";

//import di mainbox-3
import MainBox3 from "./main-components/MainBox3.vue";

export default {
    name: "AppMain",

    components: {
        MainBox1,
        MainBox2,
        MainBox3,
    },

    data() {
        return {

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

        <MainBox3></MainBox3>
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
