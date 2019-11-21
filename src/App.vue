<template>
  <v-app>
    <app-Navbar></app-Navbar>
    <app-MobileApp></app-MobileApp>
    <app-Contact></app-Contact>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import MobileApp from "./components/MobileAppContainer";
import Contact from "./components/Contact"

export default {
  name: "App",

  components: {
    appNavbar: Navbar,
    appMobileApp: MobileApp,
    appContact:Contact
  },

  data: () => ({
    //
  })
};
</script>

<style></style>
