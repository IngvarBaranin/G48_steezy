<template>
    <v-app-bar app light flat absolute>
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
            >
                <v-icon style="display:block">mdi-robot</v-icon>
            </v-btn>
        </router-link>
    </v-app-bar>
</template>

<style>
</style>
