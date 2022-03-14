<template>
<div>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
      <v-col cols="12" md="6" sm="6">
        <v-row>
          <v-card class="mx-5" max-width="600" elevation="0">
            <v-card-title class="cardTitulo" style="font-size: 33px">
              Emergency Contact
            </v-card-title>
            <v-card-subtitle class="cardSub">
              <span class="txt">
                Contact one the contacts below if you or your family feel unwell
                and have similar symptoms such as Covid-19, make sure you also
                take care of yourself before reporting to us:
              </span>
            </v-card-subtitle>
          </v-card>
        </v-row>

        <v-row>
          <v-col cols="12" sm="6" md="6">
            <v-card class="mx-auto" max-width="250" outlined>
              <v-list-item three-line>
                <v-list-item-avatar tile size="40" color="blue lighten-5">
                  <v-icon class="mx-auto" x-large left color="blue darken-2">
                    mdi-phone</v-icon
                  >
                </v-list-item-avatar>
                <v-list-item-content>
                  <v-list-item-title class="text-h5 mb-1">
                    Call
                  </v-list-item-title>
                  <v-list-item-subtitle> 021.123.145.14 </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-card-actions class="ml-2 mr-2">
                <v-btn class="mx-auto" block depressed color="blue lighten-5"
                  >Call Now
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="6">
            <v-card class="mx-auto" max-width="250" outlined>
              <v-list-item three-line>
                <v-list-item-avatar tile size="40" color="blue lighten-5">
                  <v-icon class="mx-auto" x-large left color="blue darken-2">
                    mdi-chat-processing</v-icon
                  >
                </v-list-item-avatar>
                <v-list-item-content>
                  <v-list-item-title class="text-h5 mb-1">
                    Chat
                  </v-list-item-title>
                  <v-list-item-subtitle> 021.123.145.14 </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-card-actions class="ml-2 mr-2">
                <v-btn class="mx-auto" block depressed color="blue lighten-5"
                  >Chat Now</v-btn
                >
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="6">
            <v-card class="mx-auto" max-width="250" outlined>
              <v-list-item three-line>
                <v-list-item-avatar tile size="40" color="blue lighten-5">
                  <v-icon class="mx-auto" x-large left color="blue darken-2">
                    mdi-video</v-icon
                  >
                </v-list-item-avatar>
                <v-list-item-content>
                  <v-list-item-title class="text-h5 mb-1">
                    Vide Call
                  </v-list-item-title>
                  <v-list-item-subtitle> 021.123.145.14 </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-card-actions class="ml-2 mr-2">
                <v-btn class="mx-auto" block depressed color="blue lighten-5"
                  >Vide Call Now</v-btn
                >
              </v-card-actions>
            </v-card>
          </v-col>
          <v-col cols="12" sm="6" md="6">
            <v-card class="mx-auto" max-width="250" outlined>
              <v-list-item three-line>
                <v-list-item-avatar tile size="40" color="blue lighten-5">
                  <v-icon class="mx-auto" x-large left color="blue darken-2">
                    mdi-email</v-icon
                  >
                </v-list-item-avatar>
                <v-list-item-content>
                  <v-list-item-title class="text-h5 mb-1">
                    Message
                  </v-list-item-title>
                  <v-list-item-subtitle> 021.123.145.14 </v-list-item-subtitle>
                </v-list-item-content>
              </v-list-item>
              <v-card-actions class="ml-2 mr-2">
                <v-btn class="mx-auto" block depressed color="blue lighten-5">
                  Message Now</v-btn
                >
              </v-card-actions>
            </v-card>
          </v-col>
        </v-row>
      </v-col>
      <v-col cols="12" md="6" sm="6">
        <v-card class="mx-auto" max-width="700" max-height="900" elevation="0">
          <v-img
            max-height="800"
            max-width="700"
            contain
            v-bind:src="require('../assets/img/imgv3.jpg')"
          ></v-img>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
  <div><pie></pie></div>
  </div>
</template>
<script>
import pie from '../components/footer.vue';
export default {
    components:{
pie
    }
}
</script>
<style>
.cardTitulo {
  margin-bottom: 23px;
}
.cardSub {
  margin-bottom: 5px;
}
.txt {
  font-size: 18px;
}
</style>
