<template>
    <div class="advice">
        <h1 style="text-align: center">Advice</h1>
        <br>


        <v-card max-width="800px">
            <v-toolbar
            class="orange accent-1"
            dense
            flat
            >
                <v-toolbar-title class="title">
                    We are a small team, and want to start with security
                </v-toolbar-title>
            </v-toolbar>
            <v-card-text class="font-weight-bold">
                <ol class="advice-ol">
                  <li><span>Decide what is the most important thing you will protect.</span></li>
                  <li><span>What are you using for working with the most important information?</span></li>
                  <li><span>How do you want to protect your most important assets?</span></li>
                  <li><span>What technical measures do you have to do asap?</span></li>
                </ol>
            </v-card-text>
        </v-card>

        <br>

        <v-card max-width="800px">
            <v-toolbar
            class="orange accent-1"
            dense
            flat
            >
                <v-toolbar-title class="title">
                    We know our basics and want to become pros
                </v-toolbar-title>
            </v-toolbar>
            <v-card-text class="font-weight-bold">
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Security objectives are clear <br>
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Assets are counted and categorized <br>
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Security policy lookalike exists <br>

                <br>

                <ol class="advice-ol">
                  <li><span>Have you done a long-ass risk assessment?</span></li>
                  <li><span>What are the controls we might have missed?</span></li>
                  <li><span>What can we do about logging and monitoring?</span></li>
                  <li><span>Can we boost to data protection/ that GDPR thing?</span></li>
                  <li><span>Do you review application security and pentest?</span></li>
                  <li><span>Is your incident management effective?</span></li>
                </ol>
            </v-card-text>
        </v-card>

        <br>

        <v-card max-width="800px">
            <v-toolbar
            class="orange accent-1"
            dense
            flat
            >
                <v-toolbar-title class="title">
                    We are confident in managing security
                </v-toolbar-title>
            </v-toolbar>
            <v-card-text class="font-weight-bold">
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Many security documents exist <br>
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Risk assessment done  <br>
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Pentests done <br>
                <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon> Staff trained <br>

                <br>

                <ol class="advice-ol">
                  <li><span>How to start with audits or reviews?</span></li>
                  <li><span>How to follow up on your critical supplier contracts</span></li>
                  <li><span>What can we improved in DEV and OPS security?</span></li>
                  <li><span>How to assess IP, GDPR and other compliance?</span></li>
                  <li><span>Check out also other useful frameworks like business continuity.</span></li>
                </ol>
            </v-card-text>
        </v-card>


    </div>
</template>

<style>
    .iconspace {
        padding-right:1em
    }

    .advice{
        padding-right: 5vw;
    }

    .advice-ol li { color: #FFAB40; }
    .advice-ol li span {
        color: #757575;
        padding-left:1em; 
    }
</style>
