<template>
  <v-app-bar prominent fixed shrink-on-scroll elevate-on-scroll color="#ffd54c">
    <template v-slot:img>
      <v-img
        src="../images/inter_logo_transpa.png"
        height="60%"
        contain
        position="left"
        class="ma-4"
      ></v-img>
    </template>
    <template v-slot:extension
      ><v-toolbar color="transparent" class="mb-12" flat>
        <v-spacer></v-spacer>

        <v-toolbar class="mb-12 hidden-md-and-down" color="transparent" flat>
          <v-spacer></v-spacer
          ><v-btn large text rounded class="mr-2 headline font-weight-bold"
            >o nas</v-btn
          >
          <v-btn large text rounded class="mr-2 headline font-weight-bold"
            >usługi</v-btn
          >
          <v-btn
            large
            class="mr-4  headline font-weight-bold"
            rounded
            dark
            href="tel: +48757719919"
            ><v-icon large class="ml-0 mr-3" right dark>mdi-phone</v-icon
            >zadzwoń 757 719 919 lub 505 159 191</v-btn
          >
        </v-toolbar>

        <v-menu>
          <template v-slot:activator="{ on }">
            <v-app-bar-nav-icon
              large
              class="hidden-lg-and-up"
              v-on="on"
            ></v-app-bar-nav-icon>
          </template>
          <v-list color="#ffd54c"
            ><v-list-item>
              <v-list-item-title
                ><v-btn text rounded class="mr-2 font-weight-bold"
                  >o nas</v-btn
                ></v-list-item-title
              ></v-list-item
            >
            <v-list-item>
              <v-list-item-title
                ><v-btn text rounded class="mr-2 font-weight-bold"
                  >usługi</v-btn
                ></v-list-item-title
              ></v-list-item
            >
            <v-list-item>
              <v-list-item-title>
                <v-btn
                  large
                  class="mr-4 font-weight-bold"
                  rounded
                  dark
                  href="tel: +48757719919"
                  ><v-icon class="ml-0 mr-3" right dark>mdi-phone</v-icon
                  >zadzwoń</v-btn
                ></v-list-item-title
              ></v-list-item
            ></v-list
          >
        </v-menu>
      </v-toolbar>
    </template>
  </v-app-bar>
</template>
<script></script>

<style>
</style>
