<template>
  <div id="app">
    <CustomHeader />
    <CustomMain />
    <CustomFooter />
  </div>
</template>

<script>
import CustomHeader from "./components/CustomHeader.vue";
import CustomMain from "./components/CustomMain.vue";
import CustomFooter from "./components/CustomFooter.vue"

export default {
  name: "App",
  components: {
    CustomHeader,
    CustomMain,
    CustomFooter,
},
};
</script>

<style lang="scss">

</style>
