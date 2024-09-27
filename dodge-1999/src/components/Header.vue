<script>
import ChargerConcept from '@/assets/images/dodge logo 1999.png'

export default {
  data: function () {
    return {
      image: ChargerConcept,
      link: "https://github.com/matthew-simms-298/DodgeFanSite"
    }
  }
}
</script>

<template>
  <header>
    <div id="header">
      <div id="brand">
        <img :src="image" :width="150" :height="150" />
        <h1>We're All About Change</h1>
      </div>
      <a id="header-tag"> Build and Price </a>
      <a id="header-tag"> The New Charger </a>
      <a href="" id="header-tag"> Check out my Offical Website! </a>
    </div>
    <p id="dislaimer">
      Disclaimer: This website is not the official Dodge website, this is a project to showcase my
      ability using different frameworks and technologies. Feel free to check out the <a id="github" target="_blank" :href="link">GitHub!</a>
    </p>
  </header>
</template>

<style></style>
