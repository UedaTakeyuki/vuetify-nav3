<template>
  <v-app>
    <Navbar
      titleStr="Demo App" :links="links" qrExp=""
    />
    <v-main>
      アホアホ
    </v-main>
  </v-app>
</template>

<script>
import {Navbar} from '../../src/components/build-entry.js'
export default {
  components: {Navbar},
    data: () => ({
    links: [
      { icon: '', text: 'Home', route: '/'},
    ]
  }),

}
  //
</script>
