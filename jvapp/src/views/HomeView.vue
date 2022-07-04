<script setup>
import { ref } from 'vue'
</script>

<template>
  <header class="bg-black py-8 m-6">

    <div class="wrapper">

      <nav>

        <NavBar />
        <MenuIcons />

      </nav>

      
    </div>
  </header>

  <body class="">    

    <Cards />

    <SideFilter />

    
    


    
  </body>

  <footer>

  </footer>
  
</template>

<style>
@import '@/assets/base.css';


</style>
