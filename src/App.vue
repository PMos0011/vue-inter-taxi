<template>
  <v-app>
    <app-Navbar></app-Navbar>
    <app-MobileApp></app-MobileApp>
    <app-Description></app-Description>
    <app-Parallax></app-Parallax>
    <app-Contact></app-Contact>
    <app-Footer></app-Footer>
  </v-app>
</template>

<script>
import Navbar from "./components/Navbar";
import MobileApp from "./components/MobileAppContainer";
import Contact from "./components/Contact";
import Footer from "./components/Footer";
import Description from "./components/Description"
import Parallax from "./components/Parralax"

export default {
  name: "App",

  components: {
    appNavbar: Navbar,
    appMobileApp: MobileApp,
    appContact:Contact,
    appFooter:Footer,
    appDescription:Description,
    appParallax:Parallax
  },

  data: () => ({
    //
  })
};
</script>

<style></style>
