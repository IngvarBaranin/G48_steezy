<template>
    <v-sheet
            class="content"
            app
            permanent
            rounded-lg
            color="gray darken-2"
    style="margin-top: 60px">
        
        <router-view/>

    </v-sheet>
</template>

<style>
    .content {
        padding: 20px;
        width: 95vh;
        max-width: 95vh;
        max-height: 80vh;
        height: 80vh;
        overflow: auto;
    }

</style>
