<template>
  <v-app>
    <!-- Test Navbar -->
    <Navbar
      titleStr="Demo App" :links="links" qrExp="けろけろ"
    />
    <v-main>
      <router-view />
    </v-main>
  </v-app>
</template>

<script setup>
// import from main project
import Navbar from '../../src/components/Navbar.vue'
// test settings of Navbar
const links = [
      { icon: '', text: 'Home', route: '/'},
    ]
  //
</script>
