<template>
<div id="app">
    <app-header></app-header>
    <v-container>
        <v-row>
            <v-col>
            <app-servers></app-servers>
            </v-col>
            <v-col
            <app-server-details></app-server-details>
            </v-col>
        </v-row>
    </v-container>
        <app-footer></app-footer>
</div>
</template>

<script>
    import Header from './components/Header.vue';
    import Footer from './components/Footer.vue';
    import Servers from './components/Avengers.vue';
    import ServerDetails from './components/ServerDetails.vue';
    export default {
        components: {
            'app-header': Header,
            'app-servers': Servers,
            'app-server-details': ServerDetails,
            'app-footer': Footer
        }
    }
</script>

<style>
#app {
    font-family: 'Roboto', Helvetica, Arial, sans-serif;
    -webkit-font-smoothing: antialiased;
    -moz-osx-font-smoothing: grayscale;
}
</style>