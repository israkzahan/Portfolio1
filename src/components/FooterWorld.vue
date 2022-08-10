<template>
  <v-footer
    dark
    padless
  >
    <v-card
      class="flex"
      flat
      tile
    >
      <v-card-title class="teal">
        <strong class="subheading">Get connected with me on social networks!</strong>

        <v-spacer></v-spacer>
        <v-icon color="#FFFFFF" x-large class="ml-3">
                mdi-facebook
                </v-icon>
         <v-icon color="#FFFFFF" x-large class="ml-3">
                mdi-linkedin
                </v-icon>
         <v-icon color="#FFFFFF" x-large class="ml-3">
                mdi-instagram
                </v-icon>

        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          dark
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-title>

      <v-card-text class="py-2 white--text text-center">
        {{ new Date().getFullYear() }} <strong></strong>
      </v-card-text>
    </v-card>
  </v-footer>
</template>