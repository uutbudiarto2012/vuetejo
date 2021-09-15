<template>
  <v-img
    :src="require('~/assets/img/hero-banner/hero-banner-bg.png')"
    style="margin-top: -5.5% !important"
    height="700"
  >
    <v-container>
      <v-row class="mt-8">
        <v-col xs="12" sm="12" md="6">
          <v-card flat color="transparent" style="padding-top: 22%">

            <v-card-title style="font-size: 3.2rem; font-family: 'Ubuntu', serif">
              The
            </v-card-title>
            <v-carousel
              cycle
              :show-arrows="false"
              hide-delimiter-background
              hide-delimiters
              height="63"
              :interval="5000"
            >
              <v-carousel-item
                v-for="(slide, i) in slides"
                :key="i"
              >
                <v-card-title
                  class="font-weight-bold text-decoration-underline"
                  style="font-size: 3.2rem; font-family: 'Ubuntu', serif"
                >
                  {{ slide }}
                </v-card-title>
              </v-carousel-item>
            </v-carousel>
            
            <v-card-title style="font-size: 3.2rem; font-family: 'Ubuntu', serif">
              English Learning
            </v-card-title>

            <v-card-text class="mt-8" style="font-size: 1.3rem; line-height: 1.1; font-family: 'Nunito', sans-serif; padding-bottom:0">
              Learn English with Atlaz Academy, our very own Learning Management System.
            </v-card-text>

            <v-card-actions class="mt-8">
              <v-btn depressed class="ml-2" style="background-color: #FDBF47;" width="130">
                Try Atlaz
              </v-btn>
            </v-card-actions>
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </v-img>
</template>

<script>
export default {
  data: () => ({
    cycle: false,
    slides: [
      'Integrated',
      'Immersive',
      'Interactive'
    ],
  })
}
</script>

<style scoped>
.text-decoration-underline {
  text-decoration-color: #FDBF47 !important;
}
</style>
