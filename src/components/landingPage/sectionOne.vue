<template>
    <v-container>
        <v-container fluid>
            <v-row justify-md="center" no-gutters>
                <v-container fluid>
                    <v-col cols="12">
                        <v-row>
                            <v-col cols="6">
                                <v-container>
                                    <v-col cols="12">
                                        <v-container>
                                            <v-row>
                                                <h2 class="mx-3"> Fide, Get your ride faster.</h2>
                                                <v-subheader>Get your ride through facebook messenger.</v-subheader>
                                            </v-row>
                                            <v-row>
                                                <v-form>
                                                    <v-text-field label="Ride ID" placeholder="enter your ride id" rounded outlined></v-text-field>
                                                    <v-btn color="primary" large rounded>find</v-btn>
                                                </v-form>
                                            </v-row>
                                        </v-container>
                                    </v-col>
                                </v-container>                                
                            </v-col>
                            <v-col cols="6">
                                <v-img src="@/assets/landingPage-image.png"></v-img>
                            </v-col>
                        </v-row>
                    </v-col>
                </v-container>
            </v-row>
            <v-container class="my-4">
                <v-container fluid>
                    <v-row justify="center">
                        <v-icon class="blink_me">mdi-mouse</v-icon>
                    </v-row>
                </v-container>
            </v-container>
        </v-container>
    </v-container>
</template>
<style>
.blink_me {
  animation: blinker 2s linear infinite;
}

@keyframes blinker {
  50% {
    opacity: 0;
  }
}
</style>
<script>
export default {
    
}
</script>