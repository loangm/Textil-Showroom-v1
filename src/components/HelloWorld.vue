<template>
  <v-container>
    <v-row class="text-center">


      <v-col 
        class="my-6"
        cols="12">

        <v-img
          :src="require('../assets/tslogofin.png')"
          class="my-16 mx-auto"
          contain
          width="600"
        />
        
      </v-col>


      <v-col
        cols="12">

        <h2 class="mx-4 my-8">APPLICATION MOBILE</h2>
        <h2 class="mx-4 my-8">ET</h2>
        <h2 class="mx-4 my-8">SITE INTERNET</h2>
        <h2 class="mx-4 my-8">BIENTÔT DISPONIBLE</h2>

        <v-img
          :src="require('../assets/tsicons.png')"
          class="mx-auto"
          contain
          width="160"
        />

        <v-img
          :src="require('../assets/tsphon.png')"
          class="mx-auto"
          contain
          width="600"
        />

      </v-col>


    </v-row>
  </v-container>
</template>

<script>
export default {
  name: "HelloWorld",

  data: () => ({}),
};
</script>
