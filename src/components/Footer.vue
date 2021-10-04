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
          v-for="icon in icons"
          :key="icon"
          class="mx-4 my-4 white--text"
          icon
        >
          <v-icon size="24px">
            {{ icon }}
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
      icons: [
        'mdi-facebook',
        'mdi-twitter',
        'mdi-linkedin',
        'mdi-instagram',
      ],
    }),
  }
</script>