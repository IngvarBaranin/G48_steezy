<template>
    <v-sheet
            class="content"
            absolute
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
        margin-top: 15vh;
        background-size:100% 100%;
        height: 85vh;
        overflow: auto;
    }

</style>
