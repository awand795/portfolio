<template>
  <div class="home">
    <v-img
      src="../assets/background.jpg"
      dark
      eager
      lazy-src="../assets/background.jpg"
      height="590px"
    >
      <v-layout fill-height align-center>
        <v-container>
          <v-row align="center" justify="center" class="white--text text-center">
            <v-col cols="12">
              <p class="display-3 mt-4 font-weight-bold">Hi, I'm Awanda</p>
              <p class="display-2 font-weight-bold">Frontend Developer</p>
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
