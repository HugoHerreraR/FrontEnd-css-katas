<template>
  <div>
    <v-navigation-drawer v-model="sidebar" app >
      <v-list>
        <v-list-item
          v-for="item in menuItems"
          :key="item.title"
          :to="item.path"
        >
          <v-list-item-content>{{ item.title }}</v-list-item-content>
        </v-list-item>
      </v-list>
    </v-navigation-drawer>
    <v-toolbar class="margen">
      <span class="hidden-sm-and-up">
        <v-app-bar-nav-icon @click="sidebar = !sidebar"> </v-app-bar-nav-icon>
      </span>
      <v-toolbar-title>
        <router-link to="/" tag="span" style="cursor: pointer">
          {{ appTitle }}
        </router-link>
      </v-toolbar-title>
      <v-spacer></v-spacer>
      <v-toolbar-items class="hidden-xs-only">
        <v-btn
          text
          v-for="item in menuItems"
          :key="item.title"
          :to="item.path"
        >
          {{ item.title }}
        </v-btn>
      </v-toolbar-items>
    </v-toolbar>
    <div>
      <Home></Home>
      <why></why>
      <Preparation></Preparation>
      <Contact></Contact>
      <!-- <transition>
        <router-view></router-view>
      </transition> -->
    </div>
  </div>
</template>

<script>
import Home from '../views/Home.vue'
import why from '../views/Why.vue'
import Preparation from '../views/Preparation.vue'
import Contact from '../views/Contact.vue'

export default {
  // name: "HomeView",
  components: {Home, why, Preparation,Contact},
  data() {
    return {
      appTitle: "Vaccination",
      sidebar: false,
      menuItems: [
        { title: "Database", path: "#" },
        { title: "Education", path: "#" },
        { title: "News", path: "#" },
        { title: "Regulation", path: "#" },
      ],
    };
  },
  created() {},
  methods: {
     admin() {
      this.$router.push({ path:"#"});
    },
  },
  mounted() {},
};
</script>

<style>
.margen {
  margin-bottom: 25px;
}
</style>
