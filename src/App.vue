<template>
  <v-app>

    <v-toolbar scroll-toolbar-off-screen app>
      <v-toolbar-title v-text="title"></v-toolbar-title>
    </v-toolbar>

    <v-content>
      <HelloWorld/>
    </v-content>

    <v-footer class="blue darken-2">
      <v-layout row wrap align-center>
        <v-flex xs12>
          <div class="white--text ml-3">
            &copy 2018
          </div>
        </v-flex>
      </v-layout>
    </v-footer>

  </v-app>
</template>

<script>
import HelloWorld from './components/HelloWorld'

export default {
  name: 'App',
  components: {
    HelloWorld
  },
  data () {
    return {
      title: 'Itemflow'
    }
  }
}
</script>
