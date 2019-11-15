<template>
  <v-app id="landingPage">
    <HeaderNav />
    <v-content>
      <SectionOne />
    </v-content>
    <v-content>
      <SectionTwo />
    </v-content>
  </v-app>
</template>

<script>
import HeaderNav from './components/layout/HeaderNav';
import SectionOne from './components/landingPage/SectionOne';
import SectionTwo from './components/landingPage/SectionTwo';
export default {
  name: 'App',

  components: {
    HeaderNav, SectionOne, SectionTwo
  },

  data: () => ({
    //Background color
    
  }),
};
</script>
<style>
#landingPage{
  background: white;
}
</style>