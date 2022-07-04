<script setup>

import { RouterLink, RouterView } from 'vue-router'
import HelloWorld from '@/components/HelloWorld.vue'
import NavBar from '@/components/NavBar.vue'
import MenuIcons from '@/components/MenuIcons.vue'
//import SideFilter from '@/components/SideFilter.vue'
import Cards from '@/components/Cards.vue'
import HomeView from '@/views/HomeView.vue'
import Footer from '@/components/Footer.vue'
import DropdownDog from '@/components/DropdownDog.vue'
</script>

<template>


  <NavBar />
  <MenuIcons />
  <Cards />
  
  <SideFilter />            
  <!-- <DropdownDog /> -->
  <Footer /> 

  
</template>

<style>
@import '@/assets/base.css';


</style>
