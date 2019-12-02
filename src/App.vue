<template>
  <v-app>
    <app-Navbar></app-Navbar>
    <app-MobileApp></app-MobileApp>
    <app-Contact></app-Contact>
    <app-Footer></app-Footer>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import MobileApp from "./components/MobileAppContainer";
import Contact from "./components/Contact"
import Footer from "./components/Footer"

export default {
  name: "App",

  components: {
    appNavbar: Navbar,
    appMobileApp: MobileApp,
    appContact:Contact,
    appFooter:Footer
  },

  data: () => ({
    //
  })
};
</script>

<style></style>
