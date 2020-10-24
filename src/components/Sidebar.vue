<template>
    <v-navigation-drawer class="borderleft" permanent app absolute>
        <v-list-item style="height: 15vh">
            <v-list-item-content>
                <v-list-item-title class="title text-h3">
                    Steezy
                </v-list-item-title>
                <v-list-item-subtitle>
                    Cyber Security hygiene
                </v-list-item-subtitle>
            </v-list-item-content>
        </v-list-item>

        <v-divider></v-divider>
        <v-list
                dense
                nav
        >
            <router-link to="/">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Home</v-list-item-title>
                    </v-list-item-content>

                </v-list-item>
            </router-link>
            <router-link to="/overview">
                <v-list-item class="item">
                    <v-list-item-content >
                        <v-list-item-title class="text-h6 my-2 mx-4">Overview</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
            <router-link to="/advice">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Advice</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
            <router-link to="/resources">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Resources</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
            <router-link to="/contact">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Contact</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
            <router-link to="/events">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Events</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
        </v-list>
    </v-navigation-drawer>
</template>

<style>
    .borderleft {
        border-left: 2px solid #e0e0e0 !important;
    }

    .item:hover {
        background-color: #EEEEEE !important;
    }
</style>
