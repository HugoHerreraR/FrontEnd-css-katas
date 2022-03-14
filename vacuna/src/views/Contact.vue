<template>
<div>
  <v-container fill-height fluid>
    <v-row align="center" justify="center">
      <v-col cols="12" md="6" sm="6">
        <v-row>
          <v-card class="" max-width="500" elevation="0">
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
            lazy-src="https://picsum.photos/id/11/10/6"
            max-height="800"
            max-width="700"
            contain
            src="data:image/jpeg;base64,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"
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
