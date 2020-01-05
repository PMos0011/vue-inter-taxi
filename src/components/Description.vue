<template>
  <v-card flat color="#fff24c">
    <v-layout class="mt-8 mb-8" row wrap justify-center>
      <v-flex lg5 xs11 class="ml-2 mt-4" id="about-us">
        <v-hover v-slot:default="{ hover }">
          <v-card
            :elevation="hover ? 8 : 0"
            class="pb-8 pt-8 pl-2 pr-2"
            color="#fff24c"
          >
            <v-flex>
              <v-img src="../images/logo_year1933.png" contain></v-img
            ></v-flex>

            <v-flex class="text-justify pa-6 mt-8">
              <p
                :class="{
                  headline: $vuetify.breakpoint.smAndDown,
                  'display-1': $vuetify.breakpoint.mdAndUp
                }"
              >
                <b>RADIO >>INTER<< TAXI</b><br />
                to firma z tradycjami, założona w 1993 roku.
              </p>
              <p
                :class="{
                  title: $vuetify.breakpoint.smAndDown,
                  headline: $vuetify.breakpoint.mdAndUp
                }"
              >
                Doświadczenie zdobyte na przestrzeni lat pozwoliło nam
                wypracować system pracy najbardziej przyjazny dla naszych
                klientów. Dziś, idąc z duchem czasu i wychodząc na przeciw
                oczekiwaniom naszych Klientów stajemy się dla Was firmą on-line.
              </p>
              <p
                :class="{
                  title: $vuetify.breakpoint.smAndDown,
                  headline: $vuetify.breakpoint.mdAndUp
                }"
              >
                Wchodząc na naszą stronę możesz pobrać
                <a @click="elemScroll()">APLIKACJĘ</a> i zamówić taksówkę bez
                dzwonienia na infolinię. Dzięki  <a @click="elemScroll()">APLIKACJI</a> wiesz kiedy
                Twoja taksówka dojedzie na miejsce i nie musisz już czekać w
                słońcu, deszczu, na mrozie...
              </p>
              <p
                :class="{
                  title: $vuetify.breakpoint.smAndDown,
                  headline: $vuetify.breakpoint.mdAndUp
                }"
              >
                Pobierz <a @click="elemScroll()">APLIKACJĘ</a> i oszczędzaj swój czas, a my dołożymy
                starań abyś dotarł na miejsce szybko i bezpiecznie.
              </p></v-flex
            ></v-card
          ></v-hover
        >
      </v-flex>
      <v-flex lg5 xs11 class="ml-2 mt-4" id="services">
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
export default {
  methods: {
    elemScroll() {
      window.scrollTo({
        top: document.getElementById("applications").offsetTop - 150,
        behavior: "smooth"
      });
    }
  }
};
</script>

<style scoped>
.v-application a {
  font-weight: bold;
  color: black;
}
</style>
