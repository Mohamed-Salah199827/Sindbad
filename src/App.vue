<script setup>
import { RouterLink, RouterView } from 'vue-router'
import NavBarVue from './components/NavBar.vue'
import SubNavBar from './components/SubNavbar.vue'

</script>

<template>
  
 <html lang="ar" dir="rtl">
<NavBarVue/>
  <SubNavBar/>

  <RouterView />
 </html>
</template>

<style scoped>


</style>
