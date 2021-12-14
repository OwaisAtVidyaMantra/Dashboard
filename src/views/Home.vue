<template>
  <div>
    <v-container fluid>
      <v-row>
        <v-col cols="12" lg="11" class="mx-auto banner">
          <v-img
            src="../assets/hamburger.jpg"
            contain
            position="center center"
            caption="Le Catering"
          ></v-img>
          <p class="bannerCation text-h4 ma-5">Le Catering</p>
        </v-col>
      </v-row>
    </v-container>
    <about ></about>
    <!-- Footer -->
    <footer class="footer">
      <v-container fluid style="background: black">
        <v-row class="pa-10">
          <v-col>
            <p class="text-h3 text-center" style="color:#fff">
              Created by
              <mark style="background:#e85841"  >Owais</mark>
            </p>
          </v-col>
        </v-row>
      </v-container>
    </footer>
  </div>
</template>

<script>

import About from './About.vue';
export default {
  name: "Home",

  components: {  About },
};
</script>
<style scoped>
.banner {
  position: relative;
  text-align: center;
  color: white;
}
.bannerCation {
  position: absolute;
  bottom: 8px;
  left: 16px;
  font-family: serif;
  color: #666666;
}
.text-h4 {
  font-weight: 400;
  letter-spacing: 6px !important;
}
.sectionP {
  font-size: 18px !important;
  font-family: "Times New Roman", Times, serif;
  line-height: 27px !important;
  font-weight: 400 !important;
}
</style>