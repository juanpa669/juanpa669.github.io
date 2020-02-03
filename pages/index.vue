<template>
  <v-layout
    column
    justify-center
    align-center
  >
    <v-flex
      xs12
      sm8
      md6
    >
      <div class="text-center">
        <logo />
        <vuetify-logo />
      </div>
      <v-card>
        <v-card-title class="headline">
          Welcome to the juanpa.github.io start page !
        </v-card-title>
        <v-card-text>
          <p>As a web developer I like the use of Vuetify, a progressive Material Design component framework for Vue.js.</p>
          <p>
            For more information on Vuetify, check out the <a
              href="https://vuetifyjs.com"
              target="_blank"
            >
              documentation
            </a>.
          </p>
          <p>I like to develop website with VueJS wich is an amazing javascript framework !</p>
          <p>
            For more information on VueJS, check out the <a
              href="https://vuejs.com"
              target="_blank"
            >
              documentation
            </a>.
          </p>
          <p>Thanks for all developers that make it possible, thanks to Vuetify Team and VueJS Team to bringing those exciting works and features.</p>
          <div class="text-xs-right">
            <em><small>&mdash; Juan Pa</small></em>
          </div>
          <hr class="my-3">
          <br>
        </v-card-text>
        <v-card-actions>
          <v-spacer />
          <v-btn
            color="primary"
            nuxt
            to="/inspire"
          >
            Continue
          </v-btn>
        </v-card-actions>
      </v-card>
    </v-flex>
  </v-layout>
</template>

<script>
import Logo from '~/components/Logo.vue'
import VuetifyLogo from '~/components/VuetifyLogo.vue'

export default {
  components: {
    Logo,
    VuetifyLogo
  }
}
</script>
