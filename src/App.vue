<template>

<!-- App.vue -->

<v-app style="max-width: inherit;">
   <Header />
  

  <!-- Sizes your content based upon application components -->
  <v-main>

    <!-- Provides the application the proper gutter -->
    <v-container fluid>

      <!-- If using vue-router -->
      
      <router-view></router-view>
    </v-container>
  </v-main>

  <v-footer app>
    <!-- -->
  </v-footer>
</v-app>

</template>

<script>
import Header from './views/Header.vue';

export default {
  components: { Header },
  name: 'App',

  data: () => ({
    //
   
  }),
};
</script>
<style >
/* .v-application--wrap{
  max-width: inherit !important;
} */
h1, h2, h3, h4, h5, h6, p {
  font-family: 'Times New Roman', Times, serif;
}

</style>
