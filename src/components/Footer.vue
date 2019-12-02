<template>
  <v-card class="text-left" color="#ffd54c" flat>
    <v-dialog v-model="dialog" width="60%">
      <template v-slot:activator="{ on }">
        <v-btn text color="black" dark v-on="on">
          Polityka prywatności
        </v-btn>
      </template>

      <v-card>
        <v-card-title class="headline yellow lighten-2" primary-title>
          Polityka cookies
        </v-card-title>

        <v-card-text>
          <p class="bold-text">Polityka stron dotycząca ciasteczek.</p>
          <p class="normal-text">
            Niniejsza polityka cookies odnosi się do stron taxi-zgorzelec.pl,
            inter-taxi.zgorzelec.pl, inter-taxi.com.pl.
          </p>
          <p class="normal-text">
            Ciasteczka (z ang. cookies) to małe pliki, zapisywne i przechowywane
            na komputerze, tablecie lub smartphonie użytkownika podczas
            odwiedzin strony internetowej. Ciasteczko zazwyczaj zawiera nazwę
            strony internetowej, z której pochodzi, informację o „długości
            życia” ciasteczka oraz losowo wygenerowany unikalny numer służący do
            identyfikacji przeglądarki, z której następuje połączenie ze stroną
            internetową.
          </p>
          <p class="bold-text">W jakim celu i jak długo używamy ciasteczek?</p>
          <p class="normal-text">
            Do zbierania anonimowych, zagregowanych statystyk, które pozwalają
            nam zrozumieć jak ludzie używają naszej strony internetowej i
            pomagają w udoskonalaniu ich funkcjonalności i zawartości.
            Stosowanie ciasteczek nie zezwala na identyfikacji tożsamości
            użytkowników na podstawie informacji zawartych w ciasteczkach.
          </p>
          <p class="normal-text">
            Długość istnienia ciasteczek na niniejszej stronie może być sesyjna
            (na czas przeglądania strony internetowej) oraz stała (pozostające
            na urządzeniu użytkownika do momentu ich usunięcia).
          </p>
          <p class="bold-text">Ciasteczka podmiotów trzecich.</p>
          <p class="normal-text">
            Korzystając z niniejszej strony otrzymujesz ciasteczka należące do
            podmiotów zewnętrznych (Google). Więcej informacji na temat tych
            ciasteczek można znaleźć na stronie internetowe Google.
          </p>
          <p class="bold-text">
            W jaki sposób mogę zmienić ustawienia dot. ciasteczek albo je
            usunąć?
          </p>
          <p class="normal-text">
            Większość przeglądarek internetowych domyślnie ustawiona jest na
            automatyczne przyjmowanie ciasteczek. Można zmienić jednak
            ustawienia przeglądarki tak, aby ciasteczka były blokowane – w
            całości lub w jakiejś części, np. tylko od stron trzecich, albo aby
            każdorazowo otrzymywać komunikat w momencie kiedy ciasteczka są
            wysyłane na Twoje urządzenie. Pamiętaj jednak, że jeżeli zablokujesz
            używane przez nas ciasteczka, może to negatywnie wpłynąć na wygodę
            korzystania z niniejszej strony. Blokada ta uniemożliwi nam także
            zbieranie anonimowych informacji nt. używania niniejszej strony w
            celu stałego poprawiania jej zawartości.
          </p>
        </v-card-text>
      </v-card>
    </v-dialog>
    <footer>
      <cookie-law
        message="Ta strona wykorzystuje pliki cookies aby zapewnić najlepszą jakość korzystania z naszej witryny"
        theme="blood-orange--rounded"
        buttonText="Ok"
      ></cookie-law>
    </footer>
  </v-card>
</template>

<script>
import CookieLaw from "vue-cookie-law";
export default {
  components: { CookieLaw }
};
</script>

<style></style>
