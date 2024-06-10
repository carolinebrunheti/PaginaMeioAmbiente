<template>
    <div class="text-center">
      <v-dialog
        v-model="dialog"
        width="500"
      >
        <template v-slot:activator="{ on, attrs }">
          <v-btn
            color="cyan lighten-1"
            dark
            v-bind="attrs"
            v-on="on"
          >
            Contato
          </v-btn>
        </template>
  
        <v-card color="basil" >
          <v-card-title class="text-h5 grey lighten-2">
            Entre em contato
          </v-card-title>
  
          <v-card-text>
            <p>Email: meioAmbiente@hotmail.com</p>
            <p>Telefone: 3367-XX90</p>
          </v-card-text>
          <v-divider></v-divider>
  
          <v-card-actions>
            <v-spacer></v-spacer>
            <v-btn
              color="primary"
              text
              @click="dialog = false"
            >
              Fechar
            </v-btn>
          </v-card-actions>
        </v-card>
      </v-dialog>
    </div>
  </template>
  <script>
  export default {
    data () {
      return {
        dialog: false,
      }
    },
  }
</script>