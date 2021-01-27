<template>
  <div class="home">
    <HomeScreen />
  </div>
</template>
<script>
// @ is an alias to /src
import HomeScreen from "@/components/HomeScreen/HomeScreen.vue";

export default {
  name: 'Home',
  components:{
    HomeScreen
  }
}
</script>
