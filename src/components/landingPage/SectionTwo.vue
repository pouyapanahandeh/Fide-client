<template>
    <v-app>
        <v-container>
            <v-container fluid>
                <v-row justify="center">
                    <v-col cols="12">
                        <v-container>
                            <v-row justify="center" class="my-5">
                                <h1>Fide, Simple way for getting ride.</h1>
                            </v-row>
                            <v-row justify="center">
                                <v-col cols="4">
                                    <v-container>
                                        <v-card class="mx-auto" max-width="400">
                                            <v-img class="white--text align-end" height="300px"
                                            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
                                            </v-img>
                                            <v-card-title>Fide Support Bot</v-card-title>
                                            <!-- <v-card-subtitle class="pb-0">Number 10</v-card-subtitle> -->

                                            <v-card-text class="text--primary">
                                            <div>7/24 Ready to answers your questions.</div>
                                            </v-card-text>
                                        </v-card>
                                    </v-container>
                                </v-col>
                                <v-col cols="4">
                                                                        <v-container>
                                        <v-card class="mx-auto" max-width="400">
                                            <v-img class="white--text align-end" height="300px"
                                            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
                                            </v-img>
                                            <v-card-title>Fide Driver Bot</v-card-title>
                                            <!-- <v-card-subtitle class="pb-0">Number 10</v-card-subtitle> -->

                                            <v-card-text class="text--primary">
                                            <div>Verify Your account and start making money.</div>
                                            </v-card-text>
                                        </v-card>
                                    </v-container>
                                </v-col>
                                <v-col cols="4">
                                    <v-container>
                                        <v-card class="mx-auto" max-width="400">
                                            <v-img class="white--text align-end" height="300px"
                                            src="https://cdn.vuetifyjs.com/images/cards/docks.jpg">
                                            </v-img>
                                            <v-card-title>Fide Rider Bot</v-card-title>
                                            <!-- <v-card-subtitle class="pb-0">Number 10</v-card-subtitle> -->

                                            <v-card-text class="text--primary">
                                            <div>Get closest Driver to you.</div>
                                            </v-card-text>
                                        </v-card>
                                    </v-container>
                                </v-col>
                            </v-row>
                        </v-container>
                    </v-col>
                </v-row>
            </v-container>
        </v-container>
    </v-app>
</template>
<script>
  export default {
    data: () => ({
      model: null,
    }),
  }
</script>