<template>
    <v-navigation-drawer class="borderleft" permanent app absolute>
        <router-link to="/">
        <v-list-item style="height: 15vh">
            <v-list-item-content>
                <v-row no-gutters>
                    <v-col>
                        <v-list-item-subtitle class="text-h6 pl-1">
                            Security is
                        </v-list-item-subtitle>
                        <v-list-item-title class="title text-h3">
                            Steezy
                        </v-list-item-title>
                    </v-col>
                    <v-col>
                        <img src="../assets/logo.png" class="mt-2 ml-2" width="60" height="65">
                    </v-col>
                </v-row>
            </v-list-item-content>
        </v-list-item>
        </router-link>

        <v-divider></v-divider>
        <v-list
                dense
                nav
        >

            <!--<router-link to="/overview">
                <v-list-item class="item">
                    <v-list-item-content >
                        <v-list-item-title class="text-h6 my-2 mx-4">Overview</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>-->
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
            <router-link to="/events">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Events</v-list-item-title>
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

    a {
        text-decoration: none;
    }
</style>
