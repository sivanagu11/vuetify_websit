<template>
<v-app>
<v-app-bar
app 
flat
>
  
   <Header/>
</v-app-bar>
<v-content>
  <Hero/>
<gallary/>
</v-content>
</v-app>
</template>


<script>
import gallary from './components/gallary';
import Header from './components/Header';
import Hero from './components/Hero'

export default {
  name: 'App',

  components: {
    Header,
    Hero,
    gallary,
  },

  data: () => ({
    //
  }),
};
</script>
