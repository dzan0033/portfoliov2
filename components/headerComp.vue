<template>
    <div id="sectionOne">
 <!--  Navigationsbar  -->
    <v-toolbar class="elevation-0" id="header-nav" app>
        <v-toolbar-title class="elevation-0">
        <img contain id="logoimgimg" src="../assets/DBlogo.png" alt="">
        </v-toolbar-title>
      <v-spacer></v-spacer>
      <div id="navitems">
            <a href="#sectionOne" v-smooth-scroll="{duration: 3000}">HOME</a>
            <a href="#sectionTwo" v-smooth-scroll="{duration: 3000, offset: -20}">BAGGRUND</a>
            <a href="#sectionThree" v-smooth-scroll="{duration: 3000, offset: 20}">PORTFOLIO</a>
            <a href="#sectionSix" v-smooth-scroll="{duration: 3000}">KONTAKT</a>
            </div>
      <v-spacer></v-spacer>
    </v-toolbar>
<!-- Navi end -->
    <v-flex id="namePosition">
    <img contain src="../assets/name.png" align="center">
    </v-flex>
    </div>
</template>

<script>
    export default {
       
    }
</script>

<style lang="scss" scoped>

#sectionOne {
    height:100vh;
}
#header-nav {
    background-color: #00000040;
}

#logoimgimg {
height:40px;
z-index: 9999;
position: absolute;
top:20px
}

#navitems {
    margin: 0 0 0 750px;
    font-family: 'Belleza', sans-serif;
    font-size: 17px;
}

#navitems a{
    color:white;
    padding: 0 10px;
    text-decoration: none;
}

#namePosition{
    /*margin-top: 140px;*/
    padding-top:140px;
}
</style>