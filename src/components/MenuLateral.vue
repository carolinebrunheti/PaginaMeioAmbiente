<template>
    <v-card
      elevation="12"
      width="100"
    >
      <v-navigation-drawer
        floating
        permanent
      >
    <PaginaDois></PaginaDois>
    <PaginaTres></PaginaTres>
      </v-navigation-drawer>
    </v-card>
</template>
<script>

import PaginaDois from "./PaginaDois.vue"
import PaginaTres from "./PaginaTres.vue"
  export default {
    components:{
      PaginaDois,
      PaginaTres
    },
    data () {      
    }
  }
</script>