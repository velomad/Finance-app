<template>
  <div id="app">
    <div id="nav">
      <Navbar />
      <SubNavBanner />
    </div>
    <router-view />
  </div>
</template>
<script>
import Navbar from "@/components/Navbar/Navbar.vue";
import SubNavBanner from "@/components/Navbar/SubNavBanner.vue";
export default {
  name: "App",
  components: {
    Navbar,
    SubNavBanner,
  },
};
</script>
<style>
body::-webkit-scrollbar {
  display: none;
}
</style>
