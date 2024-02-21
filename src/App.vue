<script>
//import di header
import AppHeader from "./components/AppHeader.vue";

//import main
import AppMain from "./components/main/AppMain.vue"

//import di footer
import AppFooter from "./components/footer/AppFooter.vue"

import { store } from "./store";


export default {
  components: {
    AppHeader,
    AppMain,
    AppFooter,
  },
  data() {
    return {
      store,
    };
  },
  created() {

  },
  methods: {

  },
};
</script>

<template>
  <AppHeader />
  <AppMain />
  <AppFooter />
</template>

<style lang="scss"></style>
