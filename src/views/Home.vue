<template>
    <div class="home">

        <v-row>
            <v-col>
                <h1> Taking small steps towards security with ease.</h1>

                <p style="margin-bottom: 70px">Everyone’s story is different. But we all have to roll our sleeves to protect
                    the data
                    and information we
                    work with every day.</p>

                <v-card style="margin-bottom: 70px; text-align: center">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            Why should my company care about security?
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold">
                        You may not have heaps of data and software but you can still take small steps to make sure that
                        your
                        coworkers/employees data and your client data is safe.
                    </v-card-text>
                </v-card>
                <v-card style="margin-bottom: 70px; text-align: center">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            How can we help?
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold">
                        We are here to help with the first steps. Our support and chatbots can also help you if you’re
                        already
                        past
                        the starting point and want to increase the level of your security.
                    </v-card-text>
                </v-card>



                <router-link to="/advice">
                    <v-btn
                            elevation="2"
                            outlined
                            x-large
                            class="orange accent-1"
                            style="margin-right: 10px; text-align: center; text-decoration: none"
                    >Read More!</v-btn>
                </router-link>

                <router-link to="/chatbot">
                    <v-btn
                            elevation="2"
                            outlined
                            x-large
                            class="orange accent-1"
                            style="text-align: center; text-decoration: none"
                    >Ask us a question!</v-btn>
                </router-link>

            </v-col >
            <v-col class="extra">
            </v-col>
            </v-row>

    </div>
</template>

<style>
    .home {
        padding-top:2vh;
        text-align: center;
        background-image: url("../assets/undraw_Done_checking_re_6vyx.svg");
        background-repeat: no-repeat;
        background-position: right;
    }

    @media only screen and (max-width: 1350px) {
        .home{
            background-image: none;
        }

        .extra{
            display: none;
        }

    }
</style>
