<template>
  <v-app id="landingPage">
    <HeaderNav />
    <v-content>
      <SectionOne />
    </v-content>
    <v-content>
      <SectionTwo />
    </v-content>
    <FooterNav />
  </v-app>
</template>

<script>
import HeaderNav from './components/layout/HeaderNav';
import SectionOne from './components/landingPage/SectionOne';
import SectionTwo from './components/landingPage/SectionTwo';
import FooterNav from './components/layout/FooterNav';
export default {
  name: 'App',

  components: {
    HeaderNav, SectionOne, SectionTwo, FooterNav
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