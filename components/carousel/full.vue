<template>
  <v-carousel
    cycle
    hide-delimiter-background
    show-arrows-on-hover
    delimiter-icon="mdi-minus"
  >
    <template v-slot:prev="{ on, attrs }">
      <v-btn color="success" v-bind="attrs" v-on="on">Previous slide</v-btn>
    </template>
    <template v-slot:next="{ on, attrs }">
      <v-btn color="info" v-bind="attrs" v-on="on">Next slide</v-btn>
    </template>
    <v-carousel-item v-for="(slide, i) in slides" :key="i">
      <v-sheet>
        <v-row class="fill-height" align="center" justify="center">
          <img
            src="https://www.stbanklaos.la/upload/carousel/1621331170.jpg"
            style="width: 100%"
            alt=""
            srcset=""
          />
        </v-row>
      </v-sheet>
    </v-carousel-item>
  </v-carousel>
</template>
<script>
export default {
  data() {
    return {
      colors: [
        "indigo",
        "warning",
        "pink darken-2",
        "red lighten-1",
        "deep-purple accent-4",
      ],
      slides: ["First", "Second", "Third", "Fourth", "Fifth"],
    };
  },
};
</script>