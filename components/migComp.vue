<template>
  <v-container id="sectionTwo">
    <v-layout justify-center row wrap> 
      <v-flex  justify-center row>

<!-- Mit billede-->
    <v-layout align-center justify-center column fill-height> 
        <p class="om">Om</p>
        <p class="mig">mig</p>
        <img id="photo" src="../assets/img/photo.jpg">
    </v-layout>
      </v-flex>

<!-- Text Beskrivelse-->
      <v-flex id="beskrivelse">
          <div class="beskriv1">
          Jeg er multimediedesign studerende med en stor passion for grafisk 
          design og digital kommunikation. Jeg har fokus på front-end kodning og 
          konceptudvikling. Jeg designer og leverer visual branding og rebranding. 
          Samtidig tilbyder jeg design af website, SoMe content og pakkeløsninger 
          til print materiale, samt andet online PR materiale. </div>
          
          <div class="beskriv1">
          Min kærlighed for design og det kreative driver min vilje til at skabe 
          de bedste resultater og videreudvikle mine kompetencer. Jeg har i mange 
          år arbejdet i en branche hvor den visuelle præsentation har haft en stor 
          påvirkning virksomheden vækst, og derfor ved jeg hvad der skal til for 
          at fange brugerens opmærksomhed og levere de bedste resultater. </div>

<!-- Signatur -->
          <v-layout align-end justify-end column>
              <v-flex>
              <img id="sign" src="../assets/img/sign.png"/>
              </v-flex>
          </v-layout>
          
<!-- Modalbox CV-->
<v-layout row wrap>
          <v-layout id="mofo" align-center justify-center>
          <v-flex md6 ml-5>
            <div class="text-xs-center" >
    <v-dialog v-model="dialog" width="1000">
      

      <template v-slot:activator="{ on }">
        <p id="textCV" v-on="on">CV</p>
      </template>

      
      <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div id="colorBox" style="height:120px; background-color:#C3B1A6; z-index: 2;"></div> 
          <v-layout align-start justify-end row fill-height>
          <v-btn color="white" flat @click="dialog = false">
           <h1>X</h1>
            
          </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cv1" src="../assets/img/cv2.jpg">
          </v-flex>
        <v-flex md12>
            <img contain id="cv3" src="../assets/img/cv1.jpg">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#D7CCC4;"></div> 
        </v-card>
    </v-dialog>
  </div>
  </v-flex>
  </v-layout>

<!-- Modalbox Visitkort-->      
            <v-layout align-center justify-center>
          <v-flex md6 ml-5>
            <div class="text-xs-center" >
    <v-dialog v-model="dialogTwo" width="1000">
      

      <template v-slot:activator="{ on }">
        <p id="textVK" v-on="on">Visitkort</p>
      </template>

      
      <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:120px; background-color:#C3B1A6;"></div> 
          <v-layout align-start justify-end row fill-height>
          <v-btn color="white" flat @click="dialogTwo = false">
           <h1>X</h1>
            
          </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
          <v-flex md6 >
            <img contain id="cv1" src="../assets/img/vk1.jpg">
          </v-flex>
          <v-flex md6>
            <img contain id="cv3" src="../assets/img/vk2.jpg">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#D7CCC4;"></div> 
        </v-card>
    </v-dialog>
  </div>
  </v-flex>


          </v-layout> 
          </v-layout> 
      </v-flex>
    </v-layout>
  </v-container>
</template>

<!-- SCRIPT -->
<script>
  export default {
    data() {
      return {
        show: true,
        dialog: false,
        dialogTwo: false,
      }
    },
    methods: {
  
    }
  }
</script>


<!-- STYLE -->
<style lang="scss" scoped>
#mofo {
  width:10px;
}
#sectionTwo {
  height: 100vh
}
#photo{
  height: 400px;
  width: auto;
  border-radius: 30px;
  align-items: center;
}
#border{
  height: 400px;
  width: 290px;
  border: 4px solid #C3B1A6;
  border-radius: 30px;
}

.beskriv1{
  height: 100px;
  width: 400px;
  padding: 0px;
  margin: 60px;
  color: #C3B1A6;
}

#button{
  height: 70px;
}

.om{
  color: #C3B1A6;
  font-size: 100px;
  font-family: 'Belleza', sans-serif;
  line-height: 0.1;
  margin-right: 270px;
  margin-left: 150px;
}

.mig{
  color: #C3B1A6;
  font-size: 100px;
  font-family: 'Belleza', sans-serif;
  margin-left: 120px;
  line-height: 1;
}

#sign{
  height: 60px;
  margin-right: 120px;
}

#textCV{
  background-image: url('../assets/img/knap.png');
  background-size: contain;
  font-family: 'Belleza', sans-serif;
  color: white;
  font-size: 45px;
  cursor: pointer;
  min-width:220px; 
  
}

#textVK{
  background-image: url('../assets/img/knap.png');
  background-size: contain;
  font-family: 'Belleza', sans-serif;
  color: white;
  font-size: 45px;
  cursor: pointer;
  min-width:220px; 
}

#cv1{
  width: 800px;
  height:auto;
  margin-top:-40px;
  padding: 10px;
}

#cv3{
  width: 800px;
  height:auto;
  padding: 10px;
  margin-bottom: -40px;
}
</style>

