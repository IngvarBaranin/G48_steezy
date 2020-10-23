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
        margin-right: 12px;
        margin-left: 12px;
        padding: 20px;
        width: 48vw;
        max-width: 48vw;
        max-height: 70vh;
        height: 70vh;
        overflow: auto;
    }

</style>
