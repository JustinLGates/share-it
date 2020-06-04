<template>
  <div class="home container-fluid">
    <OporationsComp />
    <SlideShowComp />
  </div>
</template>

<script>
// @ is an alias to /src
import OporationsComp from "../components/OporationComp";
import SlideShowComp from "../components/slideshow";
export default {
  name: "Home",
  components: {
    OporationsComp,
    SlideShowComp
  }
};
</script>

<style>
.msg-card {
  display: inline;
  border-radius: 8px;
  background: rgba(46, 46, 46, 0.746);
  box-shadow: 2px 2px 2px black;
}
.home {
}
</style>
