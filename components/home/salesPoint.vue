<template>
  <v-container style="padding: 8rem 0 9rem 0;">

    <v-row justify="center">
      <v-col xs="12" sm="12" md="7" align="center">
        
        <v-card flat color="transparent">
          <v-card-text style="font-size: 1.75rem; line-height: 2rem; font-weight: bold; font-family: 'Nunito', sans-serif">
            Student can experience true personalized learning through Atlaz’s innovative learning environment.
          </v-card-text>
        </v-card>

      </v-col>
    </v-row>

    <v-row justify="center">

      <v-col xs="12" sm="12" md="4" align="center">
        <img
          :src="require('~/assets/img/sales-point/book.gif')"
          style="max-height: 100px"
        />
        <v-card flat color="transparent">
          <v-card-title
            class="justify-center"
            style="font-size: 1.3rem; font-weight: bold; padding-top: 0; font-family: 'Lora', serif !important"
          >
            National Curriculum Compliant
          </v-card-title>
          <v-card-text style="font-size: 1rem; font-family: 'Nunito', sans-serif; font-weight: bold">
            Atlaz matches the national curriculum and is based on CEFR international standard
          </v-card-text>
        </v-card>
      </v-col>

      <v-col xs="12" sm="12" md="4" align="center">
        <img
          :src="require('~/assets/img/sales-point/paper.gif')"
          style="max-height: 100px"
        />
        <v-card flat color="transparent">
          <v-card-title
            class="justify-center"
            style="font-size: 1.3rem; font-weight: bold; padding-top: 0; font-family: 'Lora', serif !important"
          >
            Offline, Online, or Hybrid Method
          </v-card-title>
          <v-card-text style="font-size: 1rem; font-family: 'Nunito', sans-serif; font-weight: bold">
            No matter what your preference is, Atlaz has your learning needs covered!
          </v-card-text>
        </v-card>
      </v-col>

      <v-col xs="12" sm="12" md="4" align="center">
        <img
          :src="require('~/assets/img/sales-point/content.gif')"
          style="max-height: 100px"
        />
        <v-card flat color="transparent">
          <v-card-title
            class="justify-center"
            style="font-size: 1.3rem; font-weight: bold; padding-top: 0; font-family: 'Lora', serif !important"
          >
            Great Selection of content
          </v-card-title>
          <v-card-text style="font-size: 1rem; font-family: 'Nunito', sans-serif; font-weight: bold">
            Exercises, quizzes, assessments, video lectures, interactive textbooks, we have it all!
          </v-card-text>
        </v-card>
      </v-col>

    </v-row>
  </v-container>
</template>