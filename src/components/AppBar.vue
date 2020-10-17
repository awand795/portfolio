<template>
    
    <v-app-bar
      dark
      app
    >
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-4 ml-4">A</p>
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-3">W</p>
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-2">A</p>
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-1">N</p>
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-2">D</p>
        <p class="font-weight-bold display-1 green--text mt-5 text--darken-3">A</p>
        <v-spacer></v-spacer>

        <v-btn
            @click="$vuetify.goTo('#aboutme',options )"
            text
        >
        <span>About Me</span>
        </v-btn>
    </v-app-bar>
</template>

<script>
export default {
    
}
</script>