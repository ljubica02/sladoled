<template>
    <v-container>
      <v-row>
        <v-col cols="12">
          <p class="text-center grey--text text--darken-1">
            Sve što ste željeli znati o sladoledima.
          </p>
        </v-col>
      </v-row>
      <v-row justify="center">
        <v-col cols="12" sm="6">
          <v-btn block color="indigo accent-4" @click="$router.push('/sladoledi')">
            Pregledajte okuse...
          </v-btn>
        </v-col>
      </v-row>
    </v-container>
  </template>
  
  <script>
  export default {
    name: 'LandingPage',
  };
  </script>
  
  <style scoped>
  </style>
  