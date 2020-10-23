<template>
    <v-navigation-drawer class="borderleft" permanent app absolute >
        <v-list-item style="height: 150px">
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
                    <v-list-item-content>
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
            <router-link to="contact">
                <v-list-item class="item">
                        <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">Contact</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
            <router-link to="news">
                <v-list-item class="item">
                    <v-list-item-content>
                        <v-list-item-title class="text-h6 my-2 mx-4">News</v-list-item-title>
                    </v-list-item-content>
                </v-list-item>
            </router-link>
        </v-list>
    </v-navigation-drawer>
</template>

<style>
    .borderleft {
        border-left: 1px solid #e0e0e0 !important;
    }
    .link {
        text-decoration: none;
        color: black !important;
    }

    .item:hover{
        background-color: rgb(230 230 230)!important;
    }
</style>
