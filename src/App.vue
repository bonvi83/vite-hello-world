<script>

import AppTitle from "./components/AppTitle.vue"

export default {
  data() {
    return {
      title: `Prova VUE`,
    }
  },

  components: {
    AppTitle,
  }
};
</script>


<template>
  <h2 class="red">{{ title }}</h2>
  <AppTitle></AppTitle>

</template>


<style>
  @import "./style.css";
</style>