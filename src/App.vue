<template>
  <v-app>
    <v-app-bar app color="primary" dark>
      <div class="d-flex align-center">
        <span class="mr-2">My Cool Model</span>
      </div>

      <v-spacer></v-spacer>

      <v-btn href="https://github.com/nasuhasri/irisapp" target="_blank" text>
        <span class="mr-2">Fork Me</span>
        <v-icon>mdi-open-in-new</v-icon>
      </v-btn>
    </v-app-bar>

    <v-main>
      <!-- <HelloWorld /> -->
      <HomePage />
    </v-main>
  </v-app>
</template>

<script>
// import HelloWorld from "./components/HelloWorld";
import HomePage from "./components/HomePage.vue";

export default {
  name: "App",

  components: {
    // HelloWorld,
    HomePage,
  },

  data: () => ({
    //
  }),
};
</script>
