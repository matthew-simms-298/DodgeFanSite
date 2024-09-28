<script>
import ChargerConcept from '@/assets/images/charger1999.png'

export default {
  data: function () {
    return {
      charger: ChargerConcept
    }
  }
}
</script>

<template>
  <main id="charger">
      <img width="900" :src="charger" />
      <div id="charger-info">
        <h1 id="charger-heading">The Future of Muscle.</h1>
        <p>Nobody does Muscle like a Dodge</p>
        <button id="charger-button">
          <p id="c-button">Explore the Charger R/T</p>
        </button>
    </div>
  </main>
</template>
