<template>
      <v-footer
      dark
      padless
    >
      <v-card
        class="flex"
        flat
        tile
      >
       
        <v-card-actions class="grey darken-3 justify-center">
          {{ new Date().getFullYear() }} — <strong>Vuetify</strong>
        </v-card-actions>
      </v-card>
    </v-footer>
</template>
<script>
 data: () => ({
    icons: [
      'fab fa-facebook',
      'fab fa-twitter',
      'fab fa-google-plus',
      'fab fa-linkedin',
      'fab fa-instagram',
    ],
  })
</script>

<style scoped>

</style>