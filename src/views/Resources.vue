<template>
    <div class="resources">
        <v-row>
            <v-col>
                <h1 style="text-align: left"> Resources </h1>
                <blockquote class="blockquote" style="padding:0"> <p>To help you on your journey to security we have compiled our favourite resources. From tools to documentations, here is everything to get you started making the world more secure!</p>
                </blockquote>
                <v-card style="margin-bottom: 30px">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title" style="text-align: center">
                            Start reading
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold" style="text-align: left; line-height: 30px">
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.ncsc.gov.uk/cyberessentials/advice#section_6" target="_blank"> Cyber essentials </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.cisecurity.org/controls/cis-controls-list/" target="_blank"> The 20 CIS Controls &
                            Resources </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.enisa.europa.eu/topics" target="_blank"> ENISA </a> and its <a
                            href="https://www.enisa.europa.eu/publications/cloud-computing-information-assurance-framework" target="_blank">Cloud
                        Computing Information Assurance Framework</a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>

                        <a href="https://www.aicpa.org/interestareas/frc/assuranceadvisoryservices/aicpacybersecurityinitiative.html" target="_blank">
                            SOC</a> and the <a
                            href="https://www.aicpa.org/content/dam/aicpa/interestareas/frc/assuranceadvisoryservices/downloadabledocuments/soc-for-cybersecurity-backgrounder.pdf" target="_blank">SOC
                        2 backgrounder</a><br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://iske.ria.ee/8_06" target="_blank"> ISKE portal (in Estonian) </a> <br>
                    </v-card-text>
                </v-card>

            </v-col>
            <v-col></v-col>
        </v-row>



        <v-row>
            <v-col>
                <v-card style="margin-bottom: 30px; text-align: center">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            Tools we like
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold" style="text-align: left; line-height: 30px">
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.cisecurity.org/blog/cis-csat-free-tool-assessing-implementation-of-cis-controls/" target="_blank">
                            CIS Critical Security Assessment Tool </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://binary.protect.io/" target="_blank"> Binary risk assessment </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="http://www.risk-bull.com/about.html" target="_blank"> RiskBull (IT Security risk assessment
                            toolbox) </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://shop.verinice.com/en/software/19/verinice.eval-1.20?number=10017.4&c=65" target="_blank">
                            Verynice.eval (openstandard and opensource ISMS tool) </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.eramba.org/" target="_blank"> Eramba open IT GRC </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://www.sans.org/security-resources/?msc=homepage" target="_blank"> SANS Information Security
                            Resources </a> <br>
                    </v-card-text>
                </v-card>

            </v-col>
            <v-col>

            </v-col>

        </v-row>


        <v-row>
            <v-col>
                <v-card style="margin-bottom: 30px; text-align: center">
                    <v-toolbar
                            class="orange accent-1"
                            dense
                            flat
                    >
                        <v-toolbar-title class="title">
                            For devs and ops
                        </v-toolbar-title>
                    </v-toolbar>
                    <v-card-text class="font-weight-bold" style="text-align: left; line-height: 30px">
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://owasp.org/www-project-top-ten/" target="_blank"> OWASP TOP 10 </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://docs.microsoft.com/en-us/microsoft-365/compliance/offering-it-grundschutz-workbook-germany?view=o365-worldwide" target="_blank">
                            Microsoft IT-Grundschutz compliance framework </a> (and many others)<br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://cloud.google.com/security/" target="_blank"> Google Cloud’s security model </a> <br>
                        <v-icon small color="yellow darken-2" class="iconspace">mdi-check-bold</v-icon>
                        <a href="https://docs.aws.amazon.com/whitepapers/latest/aws-overview/security-and-compliance.html" target="_blank">
                            AWS Security and Compliance </a> <br>

                    </v-card-text>
                </v-card>

            </v-col>
            <v-col>

            </v-col>
        </v-row>

    </div>
</template>

<style>
    .resources {
        background-image: url("../assets/undraw_my_answer_iw6k.svg");
        background-repeat: no-repeat;
        background-position: right;
    }

    a {
        text-decoration: none;
    }

    a:link {
        color: black;
    }

    a:visited {
        color: black;
    }

    a:hover {
        background-color: #ffd180;
    }

</style>
