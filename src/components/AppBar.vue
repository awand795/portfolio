<template>
    
    <v-app-bar
      hide-on-scroll
      absolute
      color="transparent"
      flat
      height="120px"
      dark
    >
    <v-layout justify-center>
      <v-container>
        <v-layout>
            <div class="d-flex align-center">
                <p class="font-weight-bold display-1">Awanda</p>
            </div>

            <v-spacer></v-spacer>

            <v-btn
                @click="$vuetify.goTo('#aboutme',options )"
                text
            >
                <span>About Me</span>
            </v-btn>

             <v-btn
                @click="$vuetify.goTo('#myproject',options )"
                text
            >
                <span>My Project</span>
            </v-btn>

             <v-btn
                @click="$vuetify.goTo('#contactme',options )"
                text
            >
                <span>Contact Me</span>
            </v-btn>
        </v-layout>
      </v-container>
    </v-layout>
    </v-app-bar>
</template>

<script>
export default {
    
}
</script>