<script>
//import di mainbox-1
import MainBox1 from "./main-components/MainBox1.vue"

export default {
    name: "AppMain",

    components: {
        MainBox1,
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
    <MainBox1></MainBox1>
</template>

<style lang="scss" scoped>
@use "../../styles/partials/variables" as *;
@use "../../styles/partials/mixins" as *;
</style>
