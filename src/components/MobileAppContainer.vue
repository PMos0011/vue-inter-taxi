<template>
  <v-card class="mobile-container" color="#ffd54c" flat>
    <v-layout row wrap justify-space-around id="applications"
      ><v-flex sm4 xs10> <v-img src="../images/PhoneCard.png"></v-img> </v-flex>
      <v-flex sm4 xs10>
        <a href="https://play.google.com/store/apps/details?id=pl.gda.infonet.taxizgorzelec&fbclid=IwAR1HJHwUqqWsDuldlxJtV4l7sLXVAS7COGWwyzMQa3oKpF9bMHEdXN-GWyY" target="blank"
          ><v-img
            src="../images/android-download.png"
            class="mb-12"
            width="90%"
          ></v-img></a
        ><a href="https://apps.apple.com/pl/app/taxi-zgorzelec/id1492340515?l=pl"
          ><v-img
            src="../images/btn-appstore-pl.png"
            class="mb-12"
            width="90%"
          ></v-img
        ></a>
      </v-flex>
    </v-layout>
    <h1 class="display-3 font-weight-medium mt-12 mb-12 text-center">
      Pobierz aplikację na telefon
    </h1>
    <v-card class="squares"></v-card>
  </v-card>
</template>
<script></script>

<style>
.mobile-container {
  padding-top: 350px;
}
.squares {
  background-image: url("../images/square.png");
  height: 20px;
  background-repeat: repeat;
}
</style>
