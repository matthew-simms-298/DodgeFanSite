<script setup lang="js">
  import Header from './components/Header.vue';
  import Charger from './components/ChargerPromo.vue';
  import Viper from './components/ViperPromo.vue'
  import RamTruck from './components/RamPromo.vue'
</script>

<template>
 <main id="homepage">
    <Header/>
    <div id="pagecontent">
      <Charger/>
      <Viper/>
      <RamTruck/>
  
    </div>
 </main>
</template>