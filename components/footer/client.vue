<template>
  <v-container style="padding:0;">
    <v-footer dark padless>
      <v-card flat tile class="primary white--text text-center">
        <v-card-text>
          <v-btn
            v-for="icon in icons"
            :key="icon"
            class="mx-4 white--text"
            icon
          >
            <v-icon size="24px">
              {{ icon }}
            </v-icon>
          </v-btn>
        </v-card-text>

        <section>
          <v-row>
            <v-col lg="2">
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
            </v-col>
            <v-col lg="2">
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
            </v-col>
            <v-col lg="2">
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
              <v-btn text> ໂອນເງິນພາຍໃນປະເທດ </v-btn>
            </v-col>
            <v-col lg="6">
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
              <h1>ລູກຄ້າທົ່ວໄປ</h1>
            </v-col>
          </v-row>
        </section>

        <v-divider></v-divider>

        <v-card-text class="white--text">
          © 2021 —
          <strong>
            Copyright: ST Bank All Rights Reserved Designed and Developed
            Vientiane Lao P.D.R</strong
          >
        </v-card-text>
      </v-card>
    </v-footer>
  </v-container>
</template>
<script>
export default {
  data: () => ({
    icons: ["mdi-facebook", "mdi-twitter", "mdi-linkedin", "mdi-instagram"],
  }),
};
</script>