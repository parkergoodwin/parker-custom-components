<template>
<div>

    <v-card
        max-width="600" class="mx-auto avengerCards" v-for="index in 5" :key = "index">
        <v-card-title>Avenger #{{ index }}</v-card-title>
        <v-card-text>Info for Avenger # {{ index }}</v-card-text>
    </v-card>

</div>
</template>

<script>
</script>

<style scoped>
.avengerCards {
    color: black;
    background-color: teal;
    margin: 15px;
}
</style>