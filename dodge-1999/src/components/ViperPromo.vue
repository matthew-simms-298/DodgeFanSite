<script>
import ChargerConcept from '@/assets/images/viperACR.png'

export default {
  data: function () {
    return {
      image: ChargerConcept
    }
  }
}
</script>

<template>
  <main id="promo">
    <div id="promo-info">
      <h1>The Heart and Soul of a Champion.</h1>
      <p>
        The Viper GTS Coupe and RT/10 roadster are no-nonsense thrill seekers that will bite you at
        any moment. With a 450 HP V10 and a 5-speed manual transmission, the Viper will deliver unrivaled performance. Can you
        handle the power?
      </p>
      <button>
        <p id="standard">Build your own</p>
      </button>
    </div>
      <img width="900" :src="image" />
      
  </main>
</template>

<style></style>
