<template>
  <v-card flat color="#fff24c">
    <v-layout class="mt-8 mb-8" row wrap justify-center>
      <v-flex lg5 xs11 class="ml-2 mt-4">
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-8 pt-8 pl-2 pr-2"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs10 sm5 class="mt-4">
                <v-img src="../images/inter_logo_transpa.png" contain></v-img
              ></v-flex>
              <v-flex xs10 sm6 class="mt-4">
                <p class="display-1 font-weight-black mt-n2">ROK ZAŁOŻENIA 1933</p>
              </v-flex></v-layout
            >
            <v-flex class="text-justify pa-6">
              <p class="display-1 mt-8">
                <b>RADIO >>INTER<< TAXI</b><br />
                to firma z tradycjami, założona w 1993 roku.
              </p>
              <p class="headline">
                Doświadczenie zdobyte na przestrzeni lat pozwoliło nam
                wypracować system pracy najbardziej przyjazny dla naszych
                klientów. Dziś, idąc z duchem czasu i wychodząc na przeciw
                oczekiwaniom naszych Klientów stajemy się dla Was firmą on-line.
              </p>
              <p class="headline">
                Wchodząc na naszą stronę możesz pobrać <b>APLIKACJĘ</b> i
                zamówić taksówkę bez dzwonienia na infolinię. Dzięki
                <b>APLIKACJI</b> wiesz kiedy Twoja taksówka dojedzie na miejsce
                i nie musisz już czekać w słońcu, deszczu, na mrozie...
              </p>
              <p class="headline">
                Pobierz <b>APLIKACJĘ</b> i oszczędzaj swój czas, a my dołożymy
                starań abyś dotarł na miejsce szybko i bezpiecznie.
              </p></v-flex
            ></v-card
          ></v-hover
        >
      </v-flex>
      <v-flex lg5 xs11 class="ml-2 mt-4">
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-8 pl-2 pr-2"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs2>
                <v-img src="../images/services.png" contain></v-img
              ></v-flex>
              <v-flex xs8>
                <p class="display-3 font-weight-black">Usługi</p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        >
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-4 pl-4 pr-2 mt-4"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs1>
                <v-img src="../images/people_transfer.png" contain></v-img
              ></v-flex>
              <v-flex xs10>
                <p class="headline">przewóz osób - w kraju i za granicą</p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        ><v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-4 pl-4 pr-2 mt-4"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs1>
                <v-img src="../images/party.png" contain></v-img
              ></v-flex>
              <v-flex xs10>
                <p class="headline">
                  obsługa uroczystości firmowych i rodzinnych
                </p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        >
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-4 pl-4 pr-2 mt-4"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs1>
                <v-img src="../images/wedding.png" contain></v-img
              ></v-flex>
              <v-flex xs10>
                <p class="headline">wesela</p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        >
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-4 pl-4 pr-2 mt-4"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs1>
                <v-img src="../images/shopping.png" contain></v-img
              ></v-flex>
              <v-flex xs10>
                <p class="headline">dowóz zakupów</p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        >
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-2 pt-4 pl-4 pr-2 mt-4"
            color="#fff24c"
            ><v-layout row wrap justify-space-around>
              <v-flex xs1>
                <v-img src="../images/card_payment.png" contain></v-img
              ></v-flex>
              <v-flex xs10>
                <p class="headline">
                  akceptujemy płatności kartą
                </p>
              </v-flex></v-layout
            >
          </v-card></v-hover
        >
      </v-flex></v-layout
    >
  </v-card>
</template>

<script>
export default {};
</script>

<style>

</style>
