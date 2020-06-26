<template>
  <div>
    <div class="header">
      <div class="social__icons">
        Icons here
      </div>
      <div class="logo">
        SkyCheck<span class="logo__dot">.</span>
      </div>
      <div class="search">
        Search bar here
      </div>
    </div>

    <main class="content__area">
      <div class="left__side">F</div>
      <div class="right__side">
        <div class="right__side--main">
          WEATHER
        </div>
        <div class="right__side--secondary">
          IMAGE
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
    data() {
      return {
        url: 'http://api.weatherstack.com/current',
        location: '',
        key: process.env.VUE_APP_KEY,
      }
    },

    created() {
      
    }
}
</script>
