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
            <v-list-item class="item">
                <v-list-item-content>
                    <v-list-item-title class="text-h6 my-2 mx-4"><a class="link" href="overview" >Overview</a></v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item class="item">
                <v-list-item-content>
                    <v-list-item-title class="text-h6 my-2 mx-4"><a class="link" href="advice" >Advice</a></v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item class="item">
                <v-list-item-content>
                    <v-list-item-title class="text-h6 my-2 mx-4"><a class="link" href="resources" >Resources</a></v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item class="item">
                <v-list-item-content>
                    <v-list-item-title class="text-h6 my-2 mx-4"><a class="link" href="contact" >Contact</a></v-list-item-title>
                </v-list-item-content>
            </v-list-item>
            <v-list-item class="item">
                <v-list-item-content>
                    <v-list-item-title class="text-h6 my-2 mx-4"><a class="link" href="news" >News</a></v-list-item-title>
                </v-list-item-content>
            </v-list-item>
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
