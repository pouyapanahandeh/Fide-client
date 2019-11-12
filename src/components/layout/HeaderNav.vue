<template>
    <v-container>
        <v-container fluid>
            <v-toolbar id="navbar">
                <v-toolbar-title>
                    Fide
                </v-toolbar-title>

                <v-spacer></v-spacer>

                <v-toolbar-items>
                    <v-btn class="ma-2" text>Features</v-btn>
                    <v-btn class="ma-2" text>Privacy & Safety</v-btn>
                    <v-btn class="ma-2" text>Track Rides</v-btn>
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
</style>