<template>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="444" elevation="0">
          <v-card-title class="cardTitulo" style="font-size: 33px;">
            Fight Virus
            <br />
            width Vacciones
          </v-card-title>

          <v-card-subtitle class="cardSub">
            <span class="txt">let´s stop this pandemic by killing the virus width a vaccine, don´t
            let yourself and yourself family get infected</span>
          </v-card-subtitle>

          <v-card-actions class="cardAction">
            <v-icon class="mr-1">mdi-shield-check</v-icon>
            <span class="subheading mr-2">Best protection</span>
            <v-spacer></v-spacer>
            <v-icon class="mr-1"> mdi-star</v-icon>
            <span class="subheading mr-2">Selected Vacciones</span>
          </v-card-actions>
          <v-card-actions>
            <v-icon class="mr-1"> mdi-clock-outline</v-icon>
            <span class="subheading mr-2">Schedule your vaccinations</span>
          </v-card-actions>
        </v-card>
      </v-col>
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="700" max-height="900">
 
            <v-img
              lazy-src="https://picsum.photos/id/11/10/6"
              max-height="800"
              max-width="700"
               contain
              src="https://gacetadental.com/wp-content/uploads/2021/02/Vacuna-Dentista.jpg"
            ></v-img>

        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>