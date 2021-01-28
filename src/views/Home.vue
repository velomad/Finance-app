<template>
  <div class="home">
    <HomeScreen />
    <!-- <our-products /> -->
  </div>
</template>
<script>
// @ is an alias to /src
import HomeScreen from "@/components/HomeScreen/HomeScreen.vue";
import OurProducts from '../components/OurProducts/OurProducts.vue';

export default {
  name: 'Home',
  components:{
    HomeScreen,
    OurProducts
  }
}
</script>
