<template>
  <!-- <div class="home">
    <img alt="Vue logo" src="../assets/logo.png">
    <HelloWorld msg="Welcome to Your Vue.js App"/>
  </div> -->

  <!-- <div v-html="html"></div> -->

  <Homepage msg="ValeFinance Ltd"/>

</template>

<script>
// @ is an alias to /src
// import HelloWorld from '@/components/HelloWorld.vue'
import Homepage from '@/components/Homepage.vue'

// import templateHTML from "@/components/homepage.html"

export default {
  name: 'HomeView',
  components: {
    // HelloWorld
    Homepage
  }
}
</script>

