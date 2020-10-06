<template>
  <div class="home">
    <v-img
      src="../assets/background4.jpg"
      dark
      eager
      lazy-src="../assets/background4.jpg"
    >
    <template v-slot:placeholder>
      <v-row
      class="fill-height ma-0"
      align="center"
      justify="center"
        >
        <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
      </v-row>
    </template>
      <v-layout fill-height align-center>
        <v-container>
          <v-row align="center" justify="center" class="white--text text-center">
            <v-col cols="12">
              <v-avatar size="200">
                <v-img src="../assets/awanda.jpg" 
                eager
                lazy-src="../assets/awanda.jpg" >
                <template v-slot:placeholder>
                  <v-row
                  class="fill-height ma-0"
                  align="center"
                  justify="center"
                    >
                    <v-progress-circular indeterminate color="grey lighten-5"></v-progress-circular>
                  </v-row>
              </template>
                </v-img>
              </v-avatar>
              <p class="display-2 mt-4 font-weight-bold">Awanda</p>
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
