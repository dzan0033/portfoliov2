<template>
  <v-container id="sectionThree">
    <v-layout>
      <v-flex>
         
        <div id="box">
          <v-layout align-end justify-end column>
          <v-flex>
          <img id="portfolio" src="../assets/img/portfolio.png" align="center">
          </v-flex>
          </v-layout>
        </div>        
          
<!-- projekt 1 -->       
<v-layout align-center row wrap ma-5>
          <v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogFjord" width="1000">

        <template id="modalBox" v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/fjordensdag/poster.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:360px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Plakat</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                    Mit bidrage til konkurrencen Fjordens dag 2019. Plakaten skulle indholde fokus 
                    punkter som natur, miljø, kultur, historie og sundhed. Produktet skulle anvendes 
                    som poster til markedsføring, program-oversigt og andet PR materialer i forbindelse 
                    med arrangementet.  
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:90px; padding-bottom:80px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> April 2019</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Klient:</b> Fjordens Dag</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogFjord = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cvFjord" src="../assets/img/fjordensdag/poster.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv2" src="../assets/img/fjordensdag/program1.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv2" src="../assets/img/fjordensdag/forslag.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv3" src="../assets/img/fjordensdag/bc.png">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>

<!-- projekt 2 -->
<v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogBryllup" width="1000">

        <template v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                :src="require('../assets/img/bryllup/fan.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:320px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Bryllup</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                    En kunde efterspurgte en række forskellige produkter til et asiatisk/dansk bryllup. 
                    Farverne skulle holdes neutrale, samtidig med at det asiatiske tema skulle være 
                    genkendeligt, uden at tage for meget fokus. Designet blev inspireret at japanske 
                    kirsebærtræer.   
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:90px; padding-bottom:80px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> Maj 2019</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Klient:</b> Brudepar</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogBryllup = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cv1" src="../assets/img/bryllup/fan.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv2" src="../assets/img/bryllup/menudrink.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv3" src="../assets/img/bryllup/bordkort.png">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>
        
<!-- projekt 3 -->
<v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogRose" width="1000">

        <template v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/rose/rose.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:340px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Photo</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                   Mit bidrag og vinder plakaten til årets poster konkurrence på uddannelsen. 
                   Jeg havde fokus på at skabe et billede med varme toner og dybde. Derfor 
                   valgte jeg naturalistiske produkter med både varme og mørke farver.   
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:90px; padding-bottom:55px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> Oktober 2018</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Klient:</b> EASV</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogRose = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cvStor" src="../assets/img/rose/rose.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv2" src="../assets/img/rose/frame.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv3" src="../assets/img/rose/room.png">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>

<!-- projekt 4 -->
<v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogExpo" width="1000">

        <template  v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/expo/dzana.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:280px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Portræt</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                    Personligt projekt der illustrerer fotografi med et personligt twist. 
                    Kan designes og printes efter personlige ønsker og præferencer.  
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:90px; padding-bottom:30px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> Marts 2019</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogExpo = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cvStor" src="../assets/img/expo/dzana.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv3" src="../assets/img/expo/potrait.png">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>

<!-- projekt 5 -->
<v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogLogo" width="1000">

        <template v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/logo/rsf.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:300px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Logo</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                    Logo design jeg lavede i forbindelse med film optagelser til Informercial video, 
                    til en privat ejet organisation Ren Strand Fanø.   
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:80px; padding-bottom:10px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> April 2019</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Klient:</b> RenStrandFanø</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogLogo = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         <v-layout align-center justify-center column>
           <v-flex md12>
            <img contain id="cvFjord" src="../assets/img/logo/rsf.png">
          </v-flex>
          <v-flex md12>
            <img contain id="cv3" src="../assets/img/logo/screen.png">
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>


<!-- projekt 6 -->
<v-flex xs12 sm4 md12s offset-sm3>
            <v-card>
        
        <div class="text-xs-center" >
        <v-dialog v-model="dialogSjob" width="1000">

        <template v-slot:activator="{ on }">
          <p id="textCV" v-on="on">
            <v-img
                class="white--text"
                height="200px"
                :src="require('../assets/img/sjob/sjob.png')">
            </v-img>
          </p>
        </template>

        <v-card style="border-radius: 20px;">
        <v-card-title style="background-color: #D7CCC4">
          <div style="height:360px;">
              <v-layout row wrap justify-end align-end> 
              <v-flex  lg8 style="padding-left:120px; line-height: 1.2; color:white;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 90px;">Projekt</p>
                <p id="pBeskrivelse" style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                    Projektet blev udarbejdet i forbindelse med en skoleprojekt, hvor der var fokus på at skabe 
                    en platform hvor studerende i Esbjerg havde bedre muligheder for at finde studiejobs. 
                </p>
              </v-flex>
              <v-spacer></v-spacer>
              <v-flex lg4 style="color:white; line-height:0.4; padding-left:90px; padding-bottom:35px;">
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Dato:</b> Marts 2019</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Klient:</b> EASV</p>
                <p style="font-family: 'Belleza', sans-serif; font-size: 20px;"><b>Rolle:</b> Designer</p>
          </v-flex>
          </v-layout>
          </div> 
          <v-layout style="position:absolute; right:30px" align-start justify-end row fill-height>
              <v-btn color="white" flat @click="dialogSjob = false">
              <h1>X</h1>
              </v-btn>
          </v-layout>
        </v-card-title>

         
          <v-layout ma-3 row wrap>
          <v-flex md6 pt-5 pl-5>
            <img contain id="cv2" src="../assets/img/sjob/screen1.png">
          </v-flex>
          <v-flex md6 pt-5 mt-5 style="line-height: 1.2;">
              <p style="font-family: 'Belleza', sans-serif; font-size: 30px;">Keep it simple</p>
              <p style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                Der var fokus på at gøre det tydligt hvad sidens <br>formål var. 
                Overskriften Studiejob og Esbjerg blev <br>indraget, sammen 
                med billeder som studerende <br>kunne relatere til.
              </p>
          </v-flex>
          <br>
          <v-flex md6 pt-5 mt- pl-5 style="line-height: 1.2;">
              <p style="font-family: 'Belleza', sans-serif; font-size: 30px;">Enkel søgning</p>
              <p style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                Søge funktionen skulle gøres enkel med <br>mulighed for filterering efter ønske. 
                <br>De vigtige informationer skulle synliggøres <br>bedre, for hurtig gennemgang og søgning.
              </p>
          </v-flex>
          <v-flex md6>
            <img contain id="cv2" src="../assets/img/sjob/screen2.png">
          </v-flex>
          <br>
          <v-flex md6 pt-5 pl-5>
            <img contain id="cv3" src="../assets/img/sjob/screen3.png">
          </v-flex>
          <v-flex md6 pt-5 mt-5 style="line-height: 1.2;">
              <p style="font-family: 'Belleza', sans-serif; font-size: 30px;">Ekstra hjælp</p>
              <p style="font-family: 'Belleza', sans-serif; font-size: 20px; line-height: " >
                Der skulle også være fokus på at tilbyde <br>de studerende ydeligere hjælp med at finde 
                <br>jobs. Bl.a. ved at tilbyde hjælpe med CV, <br>erfaring og jobsamtale kurser.
              </p>
          </v-flex>
        </v-layout>
          <div style="height:120px; background-color:#C3B1A6;"></div> 
        </v-card>
      </v-dialog>
      </div>
    </v-card>
</v-flex>

</v-layout>

<!-- LINE -->
        <div id="box">
          <v-layout align-start justify-start column>
          <v-flex id="line">
            <img id="line" src="../assets/img/line.png" align="center">
          </v-flex>
          </v-layout>
        </div>
      </v-flex>
    </v-layout>
  </v-container>
</template>

<script>
   export default {
    data() {
      return{
        dialogFjord: false,
        dialogBryllup: false,
        dialogRose: false,
        dialogExpo: false,
        dialogLogo: false,
        dialogSjob: false,
      }
    } 
  }
</script>

<style lang="scss" scoped>
  #sectionThree{
    max-width: 110% !important; 
  }

#pBeskrivelse{
  height: auto;
  width: 400px;
}

#box{
  height: 220px;
  width: 120%;
  margin-left:-10%;
  background-color: #D7CCC4;
}

#portfolio{
  height: 160px;
  margin-top: 30px;
}

#line{
  height: 200px;
}

#cv1{
  width: 800px;
  height:auto;
  cursor: pointer;
  margin-top:-120px;
  padding: 10px;
}

#cvFjord{
  width: 600px;
  height:auto;
  cursor: pointer;
  margin-top:-60px;
  padding: 10px;
}
 
#cvStor{
  width: 800px;
  height:auto;
  cursor: pointer;
  margin-top:-60px;
  padding: 10px;
}

#cv2{
  width: 400px;
  height:auto;
  padding: 10px;
}

#cv3{
  width: 400px;
  height:auto;
  padding: 10px;
}

#textCV{
  height:178px;
  padding: 0;
  margin: 0;
  opacity: 0.85;
  transition: 0.3s;
  filter: grayscale(100%);
}

#textCV:hover {
  opacity: 1;
  filter: none
}

#overlay{
  margin-top: -40px;
  padding: 10px;
  margin-bottom: -40px;
}

@media (min-width: 600px){
.flex.offset-sm3 {
    margin-left: 0;
}
}
</style>

