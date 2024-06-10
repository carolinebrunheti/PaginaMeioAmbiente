<template>
  <v-app class="basil">
    <v-main>
      <HomeLife/>

      <v-container> <TextInformation /></v-container>

      
    </v-main>
  </v-app>
</template>

<script>
import HomeLife from "./components/HomeLife";
import TextInformation from "./components/TextInformation";

export default {
  name: "App",

  components: {
    TextInformation,
    HomeLife,

  },

  data: () => ({
    //
  }),
};
</script>

<style>
/* Helper classes */
.basil {
  background-color: #fffbe6 !important;
}
.basil--text {
  color: #356859 !important;
}
</style>
