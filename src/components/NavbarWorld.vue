<template>
  <v-app-bar app color="00203FFF" dark flat class="px-8">
      <v-btn icon>
          <v-icon color="#A7121D">fas fa-dragon </v-icon>
      </v-btn>
      <v-spacer></v-spacer>
      <v-btn text @click="scroll('home')"> Home </v-btn>
      <v-btn text @click="scroll('education')"> Education </v-btn>
      <v-btn text @click="scroll('skills')"> Skills </v-btn>
      <v-btn text @click="scroll('projects')"> Projects </v-btn>
      <v-btn text @click="scroll('researchwork')"> Researchwork </v-btn>
      <v-btn text @click="scroll('contact')"> Contact </v-btn>
  </v-app-bar>
</template>

<script>
export default {
    methods:{
        scroll(refName) {
            const element = document.getElementById(refName);
            element.scrollIntoView({behavior:"smooth"});
        }
    }

}
</script>

<style>

</style>