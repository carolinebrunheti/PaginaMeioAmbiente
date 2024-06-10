<template>
    <v-carousel :show-arrows="false" :width="50">
      <v-carousel-item
        v-for="(item,i) in items"
        :key="i"
        :src="item.src"
      > 
      <MenuLateral></MenuLateral>
      <h6 class="text-color-white ">Creditos: Freepik</h6>
</v-carousel-item>

    </v-carousel>

  </template>
  <script>
import MenuLateral from './MenuLateral.vue';
  export default {
    components:{
      MenuLateral
    },
    data () {
      return {
        items: [
        {
            src: 'https://img.freepik.com/fotos-premium/rvore-meio-viva-e-meio-morta-em-pe-nas-areas-da-paisagem_185126-628.jpg?w=996',
          },
          {
            src: 'https://img.freepik.com/fotos-gratis/peixes-fofos-com-vegetacao_23-2150699269.jpg?w=1380&t=st=1710185393~exp=1710185993~hmac=4504f805bc189365df56a102c4a32e22dbc2e6444dcd960c78c9d6a15242b081',
          },
          {
            src: 'https://img.freepik.com/fotos-gratis/peixes-multicoloridos-nadando-em-uma-ai-generativa-de-recife-de-coral-vibrante_188544-12500.jpg?t=st=1710185763~exp=1710189363~hmac=cabc2d171da5a0cc4122079284db9651272383113a8dc9813583dc73c52ae022&w=1380',

          },
          {
            src: 'https://img.freepik.com/fotos-premium/tartaruga-eretmochelys-imbricata-flutua-debaixo-d-agua-maldivas-oceano-ndico_564276-5107.jpg?w=1060',
          },
          {
            src: 'https://img.freepik.com/fotos-gratis/lose-up-de-um-galho-de-arvore-conifera-bali-indonesia_72229-765.jpg?t=st=1710187789~exp=1710191389~hmac=e8900048e30e45c1953e442550a76996b30b13adda6c8f3ae30f7b8c24462ee5&w=1060',
          },
        ],
      }
    },
  }
</script>