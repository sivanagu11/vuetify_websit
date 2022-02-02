<template>
    <div class="heroclock">
  <v-carousel hide-delimiters cycle height="350px" >
    <v-carousel-item
      v-for="(item,i) in items"
      :key="i"
      :src="item.src"
    ></v-carousel-item>
  </v-carousel>
    </div>
</template>
 
<script>
export default {
  name: "Hero",

  data() {
    return {
      items: [
        {
          src:require('../assets/shopping-4694470_1280.jpg'),
        },
        {
          src:require('../assets/1_e-AhN7uzwpDlDsB1jtiZUw.jpeg'),
        },
        {
          src:require('../assets/5fed109e2b0292b5b141dd1863847d17.jpeg'),
        },
        
      ],
    };
  },
};
</script>
<style scoped>
.heroclock{
    position: relative;
}
.heroclock{
    @media screen and (max: width 500px;){
        height: 220px !important;
        
    }
}
</style>

