<template>
  <v-container grid-list-md text-xs ma-0 pa-0>
    <v-layout row wrap>
      <v-flex xs12 class="blue--text text--accent-2">
      
        <headerComp />
        <migComp />
        <portfolioComp />
        <prComp />
        
        <kontaktComp />
        <footerComp />
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
import headerComp from '@/components/headerComp.vue'
import migComp from '@/components/migComp.vue'
import portfolioComp from '@/components/portfolioComp.vue'
import prComp from '@/components/prComp.vue'
import kontaktComp from '@/components/kontaktComp.vue'
import footerComp from '@/components/footerComp.vue'


export default {
  name: 'home',
  data() {
    return {
      
    }
  },
  components: {
    headerComp,
    migComp,
    portfolioComp,
    prComp,
    kontaktComp,
    footerComp
  }
}
</script>
<style lang="scss">
 
</style>
