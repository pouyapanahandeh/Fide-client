<template>
  <v-app>
    <HeaderNav />
  </v-app>
</template>

<script>
import HeaderNav from './components/layout/HeaderNav';
import sectionOne from './components/landingPage/sectionOne';
export default {
  name: 'App',

  components: {
    HeaderNav, sectionOne
  },

  data: () => ({
    //
  }),
};
</script>
