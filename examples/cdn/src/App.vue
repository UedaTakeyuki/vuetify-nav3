<template>
  <v-app>
    <v-main>
      <Navbar
        titleStr="Demo App" :links="links" qrExp=""
      />
    </v-main>
  </v-app>
</template>

<script>
import {Navbar} from 'vuetify-nav3'
export default {
  components: {Navbar},
  data: () => ({
    links: [
      { icon: '', text: 'Home', route: '/'},
    ]
  }),
  mounted(){
    console.log("window", window)
  }
}
  //
</script>
