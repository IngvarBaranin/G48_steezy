<template>
    <v-sheet
            class="content"
            app
            permanent
            rounded-lg
            color="gray darken-2">
        <router-view/>

    </v-sheet>
</template>

<style>
    .content {
        padding-right: 10vh;
        padding-left: 5vh;
        margin-top: 10vh;
        background-size:100% 100%;
        width: 85vw;
        max-width: 85vw;
        height: 90vh;
        overflow: auto;
    }

</style>
