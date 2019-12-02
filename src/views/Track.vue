<template>
  <v-app>
    <HeaderNav />
    <v-content>
      <SectionOne />
    </v-content>
    <FooterNav />
  </v-app>
</template>
<script src="https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js"></script>
<script>
import HeaderNav from '@/components/layout/HeaderNav';
import SectionOne from '@/components/trackingPage/SectionOne'
import FooterNav from '@/components/layout/FooterNav';
export default {
  name: 'App',

  components: {HeaderNav, SectionOne, FooterNav},

  data: () => ({  
    
  }),
};
</script>