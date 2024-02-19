<script>
import Header from "./components/Header.vue";
import { store } from "./store";


export default {
  components: {
    Header,
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
  <Header></Header>
</template>

<style lang="scss"></style>
