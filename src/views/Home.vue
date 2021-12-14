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
    <v-container fluid class="mt-10">
      <v-row id="about">
        <v-col offset="1" cols="5">
          <v-img
            class="ml-auto"
            src="../assets/tablesetting2.jpg"
            contain
            position="top right"
            width="500"
          ></v-img>
        </v-col>
        <v-col cols="4" class="pt-10">
          <h3 class="text-center text-h4">About Catering</h3>
          <p
            class="text-body-1 text-center mt-10"
            style="letter-spacing: 4px !important"
          >
            Tradition since 1889
          </p>
          <p class="sectionP mt-5 text-justify">
            The Catering was founded in blabla by Mr. Smith in lorem ipsum dolor
            sit amet, consectetur adipiscing elit consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat. Duis aute iruredolor in
            reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla
            pariatur.We only use seasonal ingredients.
          </p>

          <p class="sectionP mt-2 text-justify" style="color: grey">
            The Catering was founded in blabla by Mr. Smith in lorem ipsum dolor
            sit amet, consectetur adipiscing elit consectetur adipiscing elit,
            sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.
            Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris
            nisi ut aliquip ex ea commodo consequat. Duis aute iruredolor in
            reprehenderit in <mark> voluptate </mark> esse cillum dolore eu
            fugiat nulla pariatur.We only use seasonal ingredients.
          </p>
        </v-col>
      </v-row>

      <v-row>
        <v-col cols="11" class="mx-auto pa-15">
          <v-divider inset></v-divider>
        </v-col>
      </v-row>

      <v-row>
        <v-col offset="2" cols="4" class="pt-10">
          <h3 class="text-center text-h3 mb-12">Our Menu</h3>
          <div>
            <p class="text-h4" style="font-size: 20px !important">Bread Basket</p>
            <p class="text-caption">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4" style="font-size: 20px !important">Honey Almond Granola with Fruits</p>
            <p class="text-caption">
              Natural cereal of honey toasted oats, raisins, almonds and dates 7.00
            </p>
          </div>

          <div>
            <p class="text-h4" style="font-size: 20px !important">Bread Basket</p>
            <p class="text-caption">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4" style="font-size: 20px !important">Blueberry Pancakes</p>
            <p class="text-caption">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4" style="font-size: 20px !important">Blueberry Pancakes</p>
            <p class="text-caption">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4" style="font-size: 20px !important">Blueberry Pancakes</p>
            <p class="text-caption">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>
        </v-col>
        <v-col cols="5">
          <v-img
            class="mr-auto"
            src="../assets/tablesetting.jpg"
            contain
            position="top left"
            width="500"
          ></v-img>
        </v-col>
      </v-row>

        <v-row>
        <v-col cols="11" class="mx-auto pa-15">
          <v-divider inset></v-divider>
        </v-col>
      </v-row>
    </v-container>
    <!-- Footer -->
    <footer class="w3-center w3-light-grey w3-padding-32">
      <p>
        Powered by
        <a
          href="https://www.w3schools.com/w3css/default.asp"
          title="W3.CSS"
          target="_blank"
          class="w3-hover-text-green"
          >w3.css</a
        >
      </p>
    </footer>
  </div>
</template>

<script>
export default {
  name: "Home",

  components: {},
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