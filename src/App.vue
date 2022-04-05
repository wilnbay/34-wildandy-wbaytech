<template>
<v-app>
   <HeaderComponents/>
 <v-main>
     <JumbotronComponents/>
     <BodyComponents/>
     <CardComponents/>
     <AboutComponents/>
 </v-main>
 <FooterComponents/>
</v-app>
</template>

<script>
import HeaderComponents from '@/components/HeaderComponents.vue';
import JumbotronComponents from './components/JumbotronComponents.vue';
import BodyComponents from '@/components/BodyComponents.vue';
import CardComponents from './components/CardComponents.vue';
import AboutComponents from './components/AboutComponents.vue';
import FooterComponents from './components/FooterComponents.vue';



export default {
  name: 'App',

  components: {
     HeaderComponents, 
     JumbotronComponents,
     BodyComponents,
     CardComponents,
     AboutComponents,
     FooterComponents,
   
  },

  data: () => ({
    //
  }),
};
</script>

