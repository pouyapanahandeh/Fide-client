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
                  <v-card>
                  <v-timeline align-top dense>
                        <v-timeline-item color="green" small>
                        <v-row class="pt-1">
                            <v-col cols="3">
                            <strong>Ride Started</strong>
                            </v-col>
                            <v-col>
                            <strong>....</strong>
                            <div class="caption">Fide from Passenger</div>
                            </v-col>
                        </v-row>
                        </v-timeline-item>
                        <v-timeline-item color="yellow accent-2" small>
                        <v-row class="pt-1">
                            <v-col cols="3">
                            </v-col>
                            <v-col>
                            <strong>Drivers Detail</strong>
                            <div class="caption mb-2">Skoda White, HU 212121</div>
                            <v-avatar>
                                <v-img
                                src="https://avataaars.io/?avatarStyle=Circle&topType=LongHairMiaWallace&accessoriesType=Sunglasses&hairColor=BlondeGolden&facialHairType=Blank&clotheType=BlazerSweater&eyeType=Surprised&eyebrowType=RaisedExcited&mouthType=Smile&skinColor=Pale"
                                ></v-img>
                            </v-avatar>
                            </v-col>
                        </v-row>
                        </v-timeline-item>
                        <v-timeline-item color="light-blue darken-4" small>
                        <v-row class="pt-1">
                            <v-col cols="3">
                            <strong>Ride Has Been ended</strong>
                            </v-col>
                            <v-col>
                            <strong>Tracking System is Deactive now.</strong>
                            </v-col>
                        </v-row>
                        </v-timeline-item>
                    </v-timeline>
                  </v-card>
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