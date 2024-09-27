<script>
import ChargerConcept from '@/assets/images/viperACR.png'

export default {
  data: function () {
    return {
      charger: ChargerConcept
    }
  }
}
</script>

<template>
  <main id="viper">
    <div id="viper-info">
      <h1 id="viper-heading">The Heart and Soul of a Champion</h1>
      <p>
        The Viper GTS Coupe and RT/10 roadster are no-nonsense thrill seekers that will bite you at
        any moment. With a 450 HP V10 and a 5-speed manual transmission, the Viper will deliver unrivaled performance. Can you
        handle the power?
      </p>
      <button>
        <p id="standard">Build your own</p>
      </button>
    </div>
    <img width="900" :src="charger" />
  </main>
</template>

<style></style>
