<script>
import AppHeader from "./components/AppHeader.vue";

//import main
import AppMain from "./components/main/AppMain.vue"

import { store } from "./store";


export default {
  components: {
    AppHeader,
    AppMain,
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
</template>

<style lang="scss"></style>
