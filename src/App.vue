<template>
  <v-app>
    <v-content style="background: #dc7ded">
      <Logo/>
    </v-content>
  </v-app>
</template>

<script>
import Logo from './components/Logo'

export default {
  name: 'App',
  components: {
    Logo
  },
  data () {
    return {
      //
    }
  }
}
</script>
