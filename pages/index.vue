<template>
  <div>
    <carousel-full></carousel-full>
    <v-container>
      <section>
        <v-row no-gutters>
          <v-col lg="4">
            <card-transparent></card-transparent>
          </v-col>
          <v-col lg="8">
            <v-row no-gutters>
              <v-col lg="4" sm="12" v-for="i in 6" :key="i">
                <card-transparent></card-transparent>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </section>
      <section id="post-content">
        <v-row>
          <v-col lg="6">
            <card-transparent></card-transparent>
          </v-col>
          <v-col lg="6">
            <v-row no-gutters>
              <v-col lg="6" sm="12" v-for="i in 4" :key="i">
                <card-transparent></card-transparent>
              </v-col>
            </v-row>
          </v-col>
        </v-row>
      </section>
    </v-container>
  </div>
</template>

<script>
export default {};
</script>

<style>
</style>