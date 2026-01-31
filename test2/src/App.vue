<template>
  <v-app>
    <Navbar
      titleStr="Demo App" :links="links" qrExp=""
    />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup>
import Navbar from '../../src/components/Navbar.vue'
const links = [
      { icon: '', text: 'Home', route: '/'},
    ]
  //
</script>
