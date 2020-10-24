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
        margin-top: 10vh;

        padding: 20px;
        width: 50vw;
        max-width: 50vw;
        max-height: 70vh;
        height: 70vh;
        overflow: auto;
    }

</style>
