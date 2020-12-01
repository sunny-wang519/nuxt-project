<template>
  <div class="index">
    <Nav />
    <Banner />
    <Home />
  </div>
</template>

<script>
import Nav from "./home/Nav";
import Banner from "./home/Banner";
import Home from "./home/index";

export default {
  components: {
    Nav,
    Banner,
    Home,
  },
};
</script>
<style lang="stylus" scoped>
.index {
  height: auto;
  background-color: #FFFFCC;
}
</style>