<template>
  <div id="app" class="bg-lighti">
    <HeaderComp />
    <router-view class="main" />
    <FooterComp />
  </div>
</template>



<script>
import HeaderComp from "./components/HeaderComp";
import FooterComp from "./components/FooterComp";
export default {
  components: {
    HeaderComp,
    FooterComp
  }
};
</script>


<style>
#app {
  font-family: Avenir, Helvetica, Arial, sans-serif;
  text-align: center;
  display: flex;
  flex-direction: column;
  min-height: 100vh;
}
.main {
  flex-grow: 1;
}
</style>
