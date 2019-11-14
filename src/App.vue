<template>
  <v-app id="landingPage">
    <HeaderNav />
    <v-content>
      <SectionOne />
    </v-content>
  </v-app>
</template>

<script>
import HeaderNav from './components/layout/HeaderNav';
import SectionOne from './components/landingPage/SectionOne';
export default {
  name: 'App',

  components: {
    HeaderNav, SectionOne
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