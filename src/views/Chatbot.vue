<template>
    <v-row class="ma-0 pa-0">
    <v-col class="ma-0 pa-0">
        <img src="../assets/logo.png" class="center" width="90" height="90">
        <div class="chatbot">
            <amplify-chatbot :chatbotConfig="chatbotConfig" v-on:keyup.enter.native="goToBottom()" id="chatbot"></amplify-chatbot>
        </div>
    </v-col>
    </v-row>

        <!--<v-row>
            <v-col>
                <v-card class="chatbox">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            You
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold">
                        Hello. How do I guarantee user data safety?
                    </v-card-text>
                </v-card>

                <v-card class="chatbox">
                    <v-toolbar
                            class="light-blue accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            Chatbot
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold">
                        Hey! Great question! For example you can do this, or this.
                    </v-card-text>
                </v-card>

                <v-card class="chatbox">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            You
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold">
                        Thanks! Any more tips?
                    </v-card-text>
                </v-card>


                <v-card class="chatbox">
                    <v-toolbar
                            class="light-blue accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            Chatbot
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="caption">
                        (Chatbot is thinking...)
                    </v-card-text>
                </v-card>

            </v-col>
            <v-col style="text-align: center; margin: auto auto">
                <v-btn
                        elevation="2"
                        x-large
                        type="submit"
                        v-on:click="openForm()"
                > Ask a question!
                </v-btn>

                <div class="chat-popup" id="myForm">
                    <v-card
                            elevation="2"
                            outlined
                    >
                        <form>

                            <v-textarea
                                    style="padding:10px"
                                    background-color="white"
                                    required
                                    name="msg"
                                    outlined
                                    label="Ask a question!"
                                    value=""
                            ></v-textarea>
                            <v-row class="buttons">
                                <v-col>
                                    <v-btn
                                            elevation="2"
                                            x-large
                                            type="submit"
                                    > Send
                                    </v-btn>
                                </v-col>

                                <v-col>
                                    <v-btn
                                            class="deep-orange accent-1"
                                            elevation="2"
                                            x-large
                                            type="submit"
                                            v-on:click="closeForm()"
                                    > Close
                                    </v-btn>
                                </v-col>


                            </v-row>
                        </form>
                    </v-card>
                </div>
            </v-col>
        </v-row>-->

</template>


<script>



    export default ({
        data: () => ({
            chatbotConfig: {
                bot: "OrderFlowers_dev",
                clearComplete: false
            }
        }),
        methods: {
            openForm: function () {
                document.getElementById("myForm").style.display = "block";
            },
            closeForm: function () {
                document.getElementById("myForm").style.display = "none";
            },
            goToBottom: function() {
                var element = document.getElementById("chatbot").firstChild.firstChild.firstChild;
                console.log(element);
                setTimeout(function () {
                        element.scrollTop = element.scrollHeight;
            }, 300);
            }
        }
    })
</script>

<style>
    .center {
        display: block;
        margin-left: auto;
        margin-right: auto;
    }


    .amplify-form-container {
        height: 60vh;
    }

    .amplify-form-row {
        height: 55vh;
        overflow-y: scroll;
        margin-bottom: 10px;
    }

    .amplify-interactions-input {
        background-color: #FFD180 !important;
        color: black !important;
    }

    .amplify-form-input {
        padding: 10px 10px 10px 10px;
    }

    .chatbox {
        margin-bottom: 20px;

    }

    .chatbot {
        max-width: 60vw;
        margin: 0 auto;
        max-height: 80vh;
        height: 80vh;

    }

    /* The popup chat - hidden by default */
    .chat-popup {
        display: none;
        border: 3px solid #f1f1f1;
    }

    .buttons {

        padding-bottom: 20px;
    }

    *:focus {
    outline: none;
    }

</style>
