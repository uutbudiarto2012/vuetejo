<template>
  <v-container fluid style="background-color: #E1E9F3; padding-top: 15%; padding-bottom: 10%;">
    <v-row justify="center">

      <v-col xs="12" sm="12" md="10" align="center">
        <v-row>

          <v-col xs="12" sm="12" md="7">
            <v-card flat color="transparent">
              <v-card-title style="font-size: 2.25rem; font-family: 'Ubuntu', serif !important">
                We’ll help you to get
              </v-card-title>
              <v-card-title
                class="text-decoration-underline font-weight-bold"
                style="font-size: 1.75rem; font-family: 'Nunito', serif !important"
              >
                More Effective Results
              </v-card-title>
              <v-card-text style="font-size: 1.3rem; text-align: left; line-height: 1.5rem; font-family: 'Nunito', serif !important">
                The combination of elevated learning motivation, Atlaz’s innovative curriculum, and material accessibility will definitely yield more effective results.
              </v-card-text>
              <v-card-actions class="mt-5">
                <v-btn
                  depressed
                  style="background-color: #FDBF47; font-weight: bold !important; width: 150px"
                  class="ml-2"
                >
                  Try Atlaz
                </v-btn>
              </v-card-actions>
            </v-card>
          </v-col>

          <v-col xs="12" sm="12" md="5">
            <v-carousel
              cycle
              :show-arrows="false"
              hide-delimiter-background
              hide-delimiters
              :interval="5000"
              height="400"
            >
              <v-carousel-item
                v-for="(slide, i) in slides"
                :key="i"
              >
                <v-img
                  :src="slide.src"
                  class="elevation-0"
                  height="300"
                />
              </v-carousel-item>
            </v-carousel>
          </v-col>

        </v-row>
      </v-col>
    </v-row>
  </v-container>
</template>

<script>
export default {
  data: () => ({
    slides: [
      { src: require('~/assets/img/key-benefit/1.png') },
      { src: require('~/assets/img/key-benefit/2.png') },
      { src: require('~/assets/img/key-benefit/3.png') },
      { src: require('~/assets/img/key-benefit/4.png') }
    ]
  }),

  mounted() {}
}
</script>

<style scoped>
</style>
