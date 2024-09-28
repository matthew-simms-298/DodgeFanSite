<script>
import ChargerConcept from '@/assets/images/ram2500.png'

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
    <img width="610" :src="image" />
    <div id="promo-info">
      <h1>We Changed the rules.</h1>
      <p>
        Whether you need more than 7000 lbs. of towing or more passenger room. The Ram has got you covered. With many options
        like Regular or Club Cab, 6 or 8 feet of bed space or even the famous Cummins© diesel engine. The Ram 1500,
        2500 and 3500 will have just what you need. So what'll it be boss?
      </p>
      <button>
        <p id="standard">Build your own</p>
      </button>
    </div>
  </main>
</template>

<style></style>
