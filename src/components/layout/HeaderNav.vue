<template>
    <v-container>
        <v-container fluid>
            <v-toolbar id="navbar">
                <v-toolbar-title>
                    <v-img id="logo" src="@/assets/fide-logo.png" alt="fide logo"></v-img>
                </v-toolbar-title>

                <v-spacer></v-spacer>

                <v-toolbar-items>
                    <v-dialog v-model="dialog" width="800px" style="border-radius: 15px;">
                        <template v-slot:activator="{ on }">
                            <v-btn class="ma-2" color="black" v-on="on" text>Features and Pricing</v-btn>
                        </template>
                        <v-card>
                            <v-tabs fixed-tabs>
                                <v-tab>
                                    Features
                                </v-tab>
                                <v-tab-item>
                                    <v-container>
                                        <v-container fluid>
                                            <v-row justify="center" align="center">
                                                <v-col cols="10" offset="1">
                                                    <v-container>
                                                        <v-img src="@/assets/fide.png" align="center"></v-img>
                                                        <h3>Fide</h3>
                                                        <p class="my-2">Fide is a messneger chat BOt that helps you get a cab through facebook.</p>
                                                        <h3>How's it work?</h3>
                                                        <p class="my-2">Open your messenger app, Type Fide Driver/Passenger and follow the steps to get ride or passenger.</p>
                                                        <h3>How much does it cost?</h3>
                                                        <p class="my-2">Fide is free for passengers, they only need to pay for their ride. Driver also, can use BOT for free, prices will apply from April 2020.</p>
                                                        <h3>Support & Feedbacks</h3>
                                                        <p class="my-2">Type Fide Support on messenger search bar and follow the steps, in case your feedback is related to the ride you need your fide code.</p>
                                                    </v-container>
                                                </v-col>
                                            </v-row>
                                        </v-container>
                                    </v-container>
                                </v-tab-item>
                                <v-tab>
                                    Pricing
                                </v-tab>
                                <v-tab-item>
                                    <v-container>
                                        <v-container fluid>
                                            <v-row justify="center">
                                                <v-col>
                                                    <v-container>
                                                        <p class="font-weight-medium" align="center">Fide is free of charge for Driver, this price will apply From April 2020.</p>
                                                    </v-container>
                                                </v-col>
                                            </v-row>
                                            <v-row justify="center" align="center">
                                                <v-col cols="4">
                                                    <v-card max-width="344" class="mx-auto" height="350">
                                                        <v-img
                                                        alt="Basic package for driver"
                                                        src="@/assets/basic.png"
                                                        ></v-img>
                                                            <h3 align="center">Basic</h3>
                                                            <p class="font-weight-bold" align="center">
                                                                3000 ft/month
                                                            </p>
                                                        <v-card-text>
                                                            10 ride per month, free cancellation. 
                                                        </v-card-text>
                                                        <v-card-actions></v-card-actions>
                                                    </v-card>
                                                </v-col>
                                                <!-- column two -->
                                                <v-col cols="4">
                                                    <v-card max-width="344" class="mx-auto"  height="350">
                                                        <v-img
                                                        alt="standard package for driver"
                                                        src="@/assets/standard.png"
                                                        ></v-img>
                                                        <h3 align="center">Standard</h3>
                                                            <p class="font-weight-bold" align="center">
                                                                5000 ft/month
                                                            </p>
                                                        <v-card-text>
                                                            20 rides per month, free cancellation.
                                                        </v-card-text>
                                                        <v-card-actions></v-card-actions>
                                                    </v-card>
                                                </v-col>
                                                <v-col cols="4">
                                                    <v-card max-width="344" class="mx-auto" height="350">
                                                        <v-img
                                                        src="@/assets/pro.png"
                                                        ></v-img>
                                                        <h3 align="center">Pro</h3>
                                                            <p class="font-weight-bold" align="center">
                                                                10000 ft/month
                                                            </p>
                                                        <v-card-text>
                                                            unlimited Rides, free cancellation and include insurance.
                                                        </v-card-text>
                                                        <v-card-actions></v-card-actions>
                                                    </v-card>
                                                </v-col>
                                            </v-row>
                                        </v-container>
                                    </v-container>
                                </v-tab-item>
                            </v-tabs>
                            <v-card-actions>
                            <v-spacer></v-spacer>
                            <v-btn text @click="dialog = false">
                                <v-icon>mdi-close-circle-outline</v-icon>
                            </v-btn>
                            </v-card-actions>
                        </v-card>
                        </v-dialog>
                    <v-btn class="ma-2" to="/track" text>Track Rides</v-btn>
                </v-toolbar-items>
            </v-toolbar>
        </v-container>
    </v-container>
</template>
<style>
#navbar{
    border-width: 0px;
    -webkit-box-shadow: 0px 0px;
    box-shadow: 0px 0px;
    background-color: rgba(0,0,0,0.0);
    background-image: -webkit-gradient(linear, 50.00% 0.00%, 50.00% 100.00%, color-stop( 0% , rgba(0,0,0,0.00)),color-stop( 100% , rgba(0,0,0,0.00)));
    background-image: -webkit-linear-gradient(270deg,rgba(0,0,0,0.00) 0%,rgba(0,0,0,0.00) 100%);
    background-image: linear-gradient(180deg,rgba(0,0,0,0.00) 0%,rgba(0,0,0,0.00) 100%);
}

#logo{
    width: 100px;
    height: auto;
}

</style>
<script>
  export default {
    data () {
      return {
        dialog: false,
      }
    },
  }
</script>