<template>
  <div>
    <v-app-bar color="white"  light>
      <v-app-bar-nav-icon
        class="d-lg-none d-md-none d-block"
        @click.stop="drawer = !drawer"
      ></v-app-bar-nav-icon>

      <v-toolbar-title class="text-title">Gaurment Au Catering</v-toolbar-title>

      <v-spacer></v-spacer>

      <v-tabs
        class="mr-3 d-none d-sm-none d-lg-block d-md-block"
        style="max-width: fit-content"
      >
        <v-tab href="#about"> About</v-tab>

        <v-tab> Menu</v-tab>

        <v-tab> Contact </v-tab>
      </v-tabs>
    </v-app-bar>

    <v-navigation-drawer v-model="drawer" left absolute app>
      <p class="text-center text-h6 mt-5">Gaurment Au Catering</p>
      <v-list nav class="px-7">
        <v-list-item-group
          v-model="group"
          active-class="deep-purple--text text--accent-4"
        >
          <v-list-item>
            <v-list-item-title>About</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Menu</v-list-item-title>
          </v-list-item>

          <v-list-item>
            <v-list-item-title>Contact</v-list-item-title>
          </v-list-item>
        </v-list-item-group>
      </v-list>
    </v-navigation-drawer>
  </div>
</template>
<script>
export default {
  data: () => ({
    drawer: false,
    group: null,
  }),

  watch: {
    group() {
      this.drawer = false;
    },
  },
};
</script>
<style scoped>
</style>