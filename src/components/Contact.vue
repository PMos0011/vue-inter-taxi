<template>
  <v-card  color="#ffd54c" flat>
   <v-layout class="background"></v-layout>
    <v-layout class="mt-8" row wrap justify-center
      > <v-flex class="top-index" lg4 xs8>
        <p class="display-3 font-weight-medium">Kontakt</p>
        <p class="bold-text">Zamów pod numerami:</p>
        <a href="tel:+48505159191"
          ><p class="normal-text">757 719 919 lub 505 159 191</p></a
        >
        <p class="bold-text">lub napisz:</p>
        <a href=""
          ><p class="normal-text">bok@intertaxi.zgorzelec.eu</p></a
        >
      </v-flex>
      <v-flex lg4 xs8 
        ><v-card
          class="pa-2 mb-12"
          height="500px"
          flat
          color="rgba(255,255,255,0.0)"
          ><iframe
            width="100%"
            height="100%"
            src="https://www.google.com/maps/embed/v1/place?key=AIzaSyCy9r70T3NYf3PhvVflTo0_zdif2_IoIYs&q=place_id:ChIJ1WIOahrcCEcRgi4Vj3X9peA"
          ></iframe
        ></v-card> </v-flex
      ></v-layout> 
  </v-card>
</template>
<script></script>

<style>
.bold-text {
  font-size: 2em;
  font-weight: bold;
  margin-top: 1.5em;
}
.normal-text {
  font-size: 1.5em;
  text-decoration: none;
  color: black;
  
}
a {
  text-decoration: none;
}
.background {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 0;
  right: 0;
  background-image: url("../images/zgorzelec.webp");
  background-size: cover;
  opacity: 0.3;
  z-index: 0;

}
.top-index{
  z-index: 1;
}
</style>
