<template>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="700" max-height="900" elevation="0">
          <v-img
            
            max-height="800"
            max-width="700"
            contain
            v-bind:src="require('../assets/img/imgv2.jpg')"
          ></v-img>
        </v-card>
      </v-col>
      <v-col cols="12" md="6" sm="6">
        <v-row>
          <v-card class="" max-width="500" elevation="0">
            <v-card-title class="cardTitulo" style="font-size: 33px">
              Why should I vaccine
            </v-card-title>

            <v-card-subtitle class="cardSub">
              <span class="txt">
                In order to avoid any doubts about getting the COVID-19 vaccine,
                identify the following 4 benefits of COVID-19 vaccination:
              </span>
            </v-card-subtitle>
          </v-card>
        </v-row>
        <v-row>
          <v-expansion-panels class="mr-2">
            <v-expansion-panel class="mb-3">
              <v-expansion-panel-header>
                <v-col cols="1" style="padding: 0">
                  <span class="group pa-2 blue lighten-5" style="padding: 0">
                    <v-icon
                      class="mx-auto"
                      dense
                      style="padding: 0"
                      color="blue darken-2"
                    >
                      mdi-shield-remove</v-icon
                    >
                  </span>
                </v-col>
                <v-col cols="11" style="padding: 0" class="ml-5">
                  Avoid alcoholic beverages
                </v-col>
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel class="mb-3">
              <v-expansion-panel-header>
                <v-col cols="1" style="padding: 0">
                  <span class="group pa-2 blue lighten-5" style="padding: 0">
                    <v-icon
                      class="mx-auto"
                      dense
                      style="padding: 0"
                      color="blue darken-2"
                    >
                      mdi-close-box</v-icon
                    >
                  </span>
                </v-col>
                <v-col cols="11" style="padding: 0" class="ml-5">
                  Avoid stress
                </v-col>
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel class="mb-3">
              <v-expansion-panel-header>
                <v-col cols="1" style="padding: 0">
                  <span class="group pa-2 blue lighten-5" style="padding: 0">
                    <v-icon
                      class="mx-auto"
                      dense
                      style="padding: 0"
                      color="blue darken-2"
                    >
                      mdi-chart-box</v-icon
                    >
                  </span>
                </v-col>
                <v-col cols="11" style="padding: 0" class="ml-5">
                  Eat healthy food
                </v-col>
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel class="mb-3">
              <v-expansion-panel-header>
                <v-col cols="1" style="padding: 0">
                  <span class="group pa-2 blue lighten-5" style="padding: 0">
                    <v-icon
                      class="mx-auto"
                      dense
                      style="padding: 0"
                      color="blue darken-2"
                    >
                      mdi-checkbox-marked</v-icon
                    >
                  </span>
                </v-col>
                <v-col cols="11" style="padding: 0" class="ml-5">
                  Get enough sleep
                </v-col>
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
            <v-expansion-panel class="mb-3">
              <v-expansion-panel-header>
                <v-col cols="1" style="padding: 0">
                  <span class="group pa-2 blue lighten-5" style="padding: 0">
                    <v-icon
                      class="mx-auto"
                      dense
                      style="padding: 0"
                      color="blue darken-2"
                    >
                      mdi-heart</v-icon
                    >
                  </span>
                </v-col>
                <v-col cols="11" style="padding: 0" class="ml-5">
                  Exercise or physical activity
                </v-col>
              </v-expansion-panel-header>
              <v-expansion-panel-content>
                Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do
                eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut
                enim ad minim veniam, quis nostrud exercitation ullamco laboris
                nisi ut aliquip ex ea commodo consequat.
              </v-expansion-panel-content>
            </v-expansion-panel>
          </v-expansion-panels>
        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<style scoped>
@import '../assets/css/preparation.css'
</style>
