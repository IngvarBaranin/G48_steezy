<template>
    <v-app-bar app light static flat class="ma-0 pa-0" style="max-width: 86%; width: 86%; left:auto; right: auto">
        <v-spacer></v-spacer>
        <v-btn icon>
            <v-icon>mdi-magnify</v-icon>
        </v-btn>
        <v-btn icon>
            <v-icon>mdi-progress-question</v-icon>
        </v-btn>
        <router-link to="/chatbot">
            <v-btn
                    class="orange accent-1"
                    elevation="5"
                    fab
                    small
                    style="margin-right: 20px"
            >
                <v-icon style="display:block">mdi-robot</v-icon>
            </v-btn>
        </router-link>
    </v-app-bar>
</template>

<style>
</style>
