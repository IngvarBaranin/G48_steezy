<template>
  <v-app>


        <v-navigation-drawer permanent app>
            <v-list-item>
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
              <v-list-item>
                <v-list-item-content>
                  <v-list-item-title class = "text-h6 my-3 mx-4"><a href="overview">Overview</a></v-list-item-title>
                  <v-list-item-title class = "text-h6 my-3 mx-4"><a href="advice">Advice</a></v-list-item-title>
                  <v-list-item-title class = "text-h6 my-3 mx-4"><a href="resources">Resources</a></v-list-item-title>
                  <v-list-item-title class = "text-h6 my-3 mx-4"><a href="contact">Contact</a></v-list-item-title>
                  <v-list-item-title class = "text-h6 my-3 mx-4"><a href="news">News</a></v-list-item-title>
                </v-list-item-content>
              </v-list-item>
            </v-list>
        </v-navigation-drawer>

  </v-app>
</template>

<style>

</style>
