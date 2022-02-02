<template>
  <v-container class="my-16">
    <h2 class="mx-16">Gallary</h2>
    <v-row>
      <v-col v-for="item in items" :key="item.id" cols="4">
        <v-card flat tile class="d-flex">
          <v-img :src="item.src"> </v-img>
        </v-card>
      </v-col>
    </v-row>
  </v-container>
</template>
<script>
export default {
  name: "gallary",

  data() {
    return {
      items: [
        {
          id: 1,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 2,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 3,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 4,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 5,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 6,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 7,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 8,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
        {
          id: 9,
          src: require("../assets/shopping-4694470_1280.jpg"),
        },
      ],
    };
  },
};
</script>
