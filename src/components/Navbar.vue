<template>
  <v-app-bar prominent fixed shrink-on-scroll elevate-on-scroll color="#ffd54c">
    <template v-slot:img >
      <v-img
        src="../images/inter_logo.webp"
        height="60%"
        contain
        position="left"
        class="ma-4"
      ></v-img>
      
    </template>
    <template v-slot:extension 
      ><v-tabs class="mb-12" background-color="transparent">
        <v-spacer></v-spacer>
        <v-btn large text rounded class="mr-2 headline font-weight-bold" >usługi</v-btn>
        <v-btn large text rounded class="mr-2 headline font-weight-bold">o nas</v-btn>
        <v-btn large class="mr-4  headline font-weight-bold" rounded dark href="tel: +48757719919"
          ><v-icon large class="ml-0 mr-3" right dark>mdi-phone</v-icon>zadzwoń 757
          719 919 lub 505 159 191</v-btn
        >
      </v-tabs></template
    >
  </v-app-bar>
</template>
<script></script>

<style></style>
