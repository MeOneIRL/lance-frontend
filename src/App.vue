<template>
    <v-app>
        <v-content>
            <router-view></router-view>
        </v-content>
        <Footer />
    </v-app>
</template>

<script>
import Footer from './components/Footer'

export default {
    name: 'App',

    components: {
        Footer
    },

    data: () => ({
        //
    })
}

</script>
