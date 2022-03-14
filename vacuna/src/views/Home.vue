<template>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="444" elevation="0">
          <v-card-title class="cardTitulo" style="font-size: 33px;">
            <span class="txtTitle">        Fight Virus
            <br />
            width Vacciones</span>
     
          </v-card-title>

          <v-card-subtitle class="cardSub">
            <span class="txt"
              >let´s stop this pandemic by killing the virus width a vaccine,
              don´t let yourself and yourself family get infected</span
            >
          </v-card-subtitle>

          <v-card-actions class="cardAction txtAction">
            <v-icon class="mr-1 yellow lighten-4" color="yellow accent-4">mdi-shield-check</v-icon>
            <span class="subheading mr-2">Best protection</span>
            <v-spacer></v-spacer>
            <v-icon class="mr-1 txtAction yellow lighten-4" color="yellow accent-4"> mdi-star</v-icon>
            <span class="subheading mr-2">Selected Vacciones</span>
          </v-card-actions>
          <v-card-actions>
            <v-icon class="mr-1 blue lighten-5" color="blue darken-2"> mdi-clock-outline</v-icon>
            <span class="subheading mr-2 txtAction">Schedule your vaccinations</span>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="700" max-height="900" color="#118EE4">
          <v-img
            v-bind:src="require('../assets/img/imgv1.png')"
            max-height="500"
            max-width="700"
            contain
          ></v-img>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  components: {},
  name: "Home",
};
</script>
<style scoped>
@import '../assets/css/home.css';
</style>




