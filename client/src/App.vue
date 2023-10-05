<script setup lang="ts">
import { RouterLink, RouterView } from 'vue-router'
import NavBar from './components/NavBar.vue';

</script>

<template>
  <header>
    <NavBar />
  </header>
    

    <div class="container">
      <RouterView />
    </div>

  
</template>

<style scoped>

body{
  background-color: aliceBlue;
}

.container{
  background-color: white;
  box-shadow: rgba(0,0,0,0.2);
}

</style>
