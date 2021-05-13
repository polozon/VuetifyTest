<template>
  <div>
    <v-container class="grey lighten-5 mb-6">
      <v-row
        :align="align"
        no-gutters
        style="height: 150px;"
      >
        <v-col
          v-for="n in 4"
          :key="n"
          cols="12"
          xs="12"
          sm="6"
          md="6"
          lg="3"
          xl="3"
        >
          <v-card
            class="pa-2"
            outlined
            tile
          >
            A card
          </v-card>
        </v-col>
      </v-row>
    </v-container>
  </div>
</template>

<script>
  export default {
    data: () => ({
     
    }),
  }
</script>