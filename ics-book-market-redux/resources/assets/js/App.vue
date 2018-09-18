<template>

<app-welcome-component></app-welcome-component>
</template>


<script>
    import ExampleComponent from './components/ExampleComponent';
    import WelcomeComponent from './components/WelcomeComponent';
    export default {
        data() {

        },
        components: {
            appExampleComponent: ExampleComponent,
            appWelcomeComponent: WelcomeComponent
        },

    }
</script>

<style>

</style>