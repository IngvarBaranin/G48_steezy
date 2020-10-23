<template>
    <v-app>
        <v-row>
            <v-col cols="6"
                   md="3">
                <Sidebar/>
            </v-col>

            <v-col cols="12"
                   sm="6"
                   md="8">
                <Navbar/>
                <Contentbox/>
            </v-col>
        </v-row>


    </v-app>
</template>

<script>
    import Sidebar from './components/Sidebar';
    import Navbar from './components/Topbar';
    import Contentbox from './components/Contentbox';

    export default {
        name: 'App',

        components: {
            Sidebar,
            Navbar,
            Contentbox
        },

        data: () => ({
            //
        }),
    };
</script>

<style>
    body {
        width: 1200px;
        margin: 0 auto;
    }
</style>
