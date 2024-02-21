<script>
//import dello store
import { store } from "../../store"

//import footslider
import FootSlider from "./footer-components/FootSlider.vue"

//import footlists
import FootLists from "./footer-components/FootLists.vue"

export default {
    name: "Appfooter",

    components: {
        FootSlider,
        FootLists,
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
        <FootLists></FootLists>
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
