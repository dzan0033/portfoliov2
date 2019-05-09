<template>
  <v-app>
    
     <v-content id="bgbg">
      <router-view/>
    </v-content> 
  </v-app>
</template>

<script>
//import header from './components/header.vue'


export default {
  name: 'App',

  components: {
   // 'webapp-header':header
  },
  data () {
    return {
      //
    }
  }
}
</script>
<style>
  #bgbg {
    background-image: url("../src/assets/img/bg.jpg");
    background-size: contain;  /* cover */
  }
  .container {
    max-width:100% !important
  }
</style>
