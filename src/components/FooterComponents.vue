<template>
<v-container class="footer">
  <v-footer
    
    padless
  >
    <v-card
      class="flex"
      flat
      tile
    >
      <v-card-title class="">
        <strong class="">Get connected with us on social networks!</strong>

        <v-spacer></v-spacer>

        <v-btn
          v-for="icon in icons"
          :key="icon"
          class="mx-4"
          black
          icon
        >
          <v-icon size="24px">
            {{ icon }}
          </v-icon>
        </v-btn>
      </v-card-title>

      <v-card-text class="py-2 black--text text-center">
          <strong>Copyright 2022 - Wbaytech</strong>
          
      </v-card-text>
    </v-card>
  </v-footer>
</v-container>
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

<style scoped>
.footer{
    font-family: poppins;
}
</style>