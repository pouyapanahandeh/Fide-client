<template>
  <v-container>
      <v-container fluid>
          <v-row align="center" justify="center">
            <v-alert text prominent dense dismissible border="left" type="error" icon="mdi-cloud-alert">
                To use Fide in this version, you need to be added as a tester. please use fide support.
            </v-alert>
          </v-row>
          <v-row justify="center" align="center">
              <v-col cols="10" offset="1">
                  
              </v-col>
          </v-row>
      </v-container>
  </v-container>
</template>
<script>
  export default {
    data () {
      return {
        e1: 0,
      }
    },
  }
</script>
<style>
#trackingCard{
    border-radius: 10px;
}
</style>