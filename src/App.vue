<template>
  <v-app>
    <v-app-bar app color="purple darken-4" dark>
      <div class="d-flex align-center pa-11">CSV-APP</div>
    </v-app-bar>
    <v-container class="pa-11">
      <Test />
    </v-container>
  </v-app>
</template>

<script>
import Test from "./components/Test.vue";
export default {
  name: "App",
  components: { Test },
};
</script>
