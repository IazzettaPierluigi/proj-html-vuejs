<script>
//import dello store
import { store } from "../../store"

//import footslider
import FootSlider from "./footer-components/FootSlider.vue"

export default {
    name: "AppFooter",

    components: {
        FootSlider,
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
    <footer>
        <FootSlider></FootSlider>
    </footer>
</template>

<style lang="scss" scoped>
@use "../../styles/partials/variables" as *;
@use "../../styles/partials/mixins" as *;

footer {
    background-color: black;
    padding-inline: 10px;
}
</style>
