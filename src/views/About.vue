<template>
 <v-container fluid class="mt-lg-10">
      <v-row id="about">
        <v-col offset-lg="1" lg="5" md="12">
          <v-img
            class="ml-auto d-lg-block d-none"
            lazy-src="../assets/tablesetting2.jpg"
            src="../assets/tablesetting2.jpg"
            contain
            position="top right"
            width="500"
          ></v-img>
        </v-col>
        <v-col cols="12" lg="4" md="12" sm="12" class="pt-lg-10">
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
            reprehenderit in
            <mark style="background: #e85841"> voluptate </mark> esse cillum
            dolore eu fugiat nulla pariatur.We only use seasonal ingredients.
          </p>
        </v-col>
      </v-row>

      <v-row>
        <v-col lg="11" cols="12" class="mx-auto pa-lg-15">
          <v-divider ></v-divider>
        </v-col>
      </v-row>

      <v-row>
        <v-col offset-lg="2" lg="4" md="6" cols="12" class="pt-10">
          <h3 class="text-center text-h3 mb-12">Our Menu</h3>
          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Bread Basket
            </p>
            <p class="text-caption text-lg-left text-center">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Honey Almond Granola with Fruits
            </p>
            <p class="text-caption text-lg-left text-center">
              Natural cereal of honey toasted oats, raisins, almonds and dates
              7.00
            </p>
          </div>

          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Bread Basket
            </p>
            <p class="text-caption text-lg-left text-center">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Blueberry Pancakes
            </p>
            <p class="text-caption text-lg-left text-center">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Blueberry Pancakes
            </p>
            <p class="text-caption text-lg-left text-center">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>

          <div>
            <p class="text-h4 text-lg-left text-center" style="font-size: 20px !important">
              Blueberry Pancakes
            </p>
            <p class="text-caption text-lg-left text-center">
              Assortment of fresh baked fruit breads and muffins 5.50
            </p>
          </div>
        </v-col>
        <v-col lg="5" md="6" cols="12">
          <v-img
          lazy-src="../assets/tablesetting.jpg"
            class="mr-lg-auto mx-auto"
            src="../assets/tablesetting.jpg"
            contain
            position="top left"
            width="500"
          ></v-img>
        </v-col>
      </v-row>

     <v-row>
        <v-col lg="11" md="12"  class="mx-auto pa-lg-15">
          <v-divider ></v-divider>
        </v-col>
      </v-row>

      <!-- contact section -->

      <v-row
        :style="
          'background: url(' +
          require('../assets/hamburger.jpg') +
          ') no-repeat; background-size:cover'
        "
        class="py-12"
      >
        <v-col offset-lg="2" lg="4" cols="12" md="6" >
          <h3 class="text-center text-h3 mb-12">Book a table</h3>
          <p class="sectionP mt-5 text-justify">
            We offer full-service catering for any event, large or small. We
            understand your needs and we will cater the food to satisfy the
            biggerst criteria of them all, both look and taste.
          </p>
          <p class="sectionP mt-2 text-justify" style="">
            Do not hesitate to contact us. Catering Service, 42nd Living St,
            43043 New York, NY You can also contact us by phone
            <mark style="background: #fff">00553123-2323</mark> or email
            <mark style="background: #fff">@catering.com</mark>, or you can send
            us a message here:
          </p>
        </v-col>
        <v-col cols="12" offset-lg="2" lg="4" md="6"  class="mx-auto">
          <booking-form></booking-form>
        </v-col>
      </v-row>
    </v-container>
</template>
<script>
import BookingForm from "../components/BookingForm.vue";
export default {
  data(){
    return{

    }
  },
 components: { "booking-form": BookingForm },
}
</script>
