<template>
  <v-footer
    dark
    padless
  >
    <v-col
      flat
      tile
      class="text-center"
    >
        <v-btn
          href="https://instagram.com/textil_showroom"
          target="_blank"
          class="mx-4 my-4"
          icon
        >
          <v-icon size="24px">
            mdi-instagram
          </v-icon>
        </v-btn>

        <v-btn
          href="https://www.snapchat.com/add/textil_paris"
          target="_blank"
          class="mx-4 my-4"
          icon
        >
          <v-icon size="24px">
            mdi-snapchat
          </v-icon>
        </v-btn>

      <v-divider></v-divider>

      <v-card-text class="white--text">
        {{ new Date().getFullYear() }} — TEXTILSHOWROOM
      </v-card-text>
    </v-col>
  </v-footer>
</template>

<script>
  export default {
    data: () => ({
    }),
  }
</script>