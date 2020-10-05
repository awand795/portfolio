<template>
  <div class="home">
    <v-img
      src="../assets/background3.jpg"
      dark
      max-height="500px"
    >
      <v-layout fill-height align-center>
        <v-container>
          <v-row align="center" justify="center" class="white--text">
            <v-col cols="12">
              <div
                :class="{'display-2 font-weight-bold ': $vuetify.breakpoint.smAndUp, 'title font-weight-bold': $vuetify.breakpoint.smAndDown}"
              >Welcome To My Page</div>
              <div
                :class="{'headline': $vuetify.breakpoint.smAndUp, 'subtitle-1': $vuetify.breakpoint.smAndDown}"
              >Look At My Project</div>
            </v-col>
          </v-row>
        </v-container>
      </v-layout>
    </v-img>
    <v-container>
      <v-row>
        <v-col cols="12">
          <h2 id="aboutme">About Me</h2>
          <p>Hi my name Awanda, i am 20 years old and i like programming, i just frontend developer love react and vue just
            and backend developer using node js, php (Laravel) and deno js
          </p>
        </v-col>
      </v-row>
    </v-container>
    <HelloWorld/>
  </div>
</template>

<script>
// @ is an alias to /src
import HelloWorld from '../components/HelloWorld'

export default {
  name: 'Home',
  components: {
    HelloWorld
  }
}
</script>
