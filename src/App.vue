<template>
  <div id="app">
    <main>
      <div class="search-box">
        <input 
        type="text" 
        class="search-bar" 
        placeholder="Search..."
        v-model="query"
        @keypress='fetchWeather'
        />
      </div>

      <div class="weather-wrap">
        <div class="location-box">
          <div class="location">Northhampton, UK</div>
          <div class="date">Monday 20 January 2020</div>
        </div>

        <div class="weather-box">
          <div class="temp">9 &#176;</div>
          <div class="weather">Rain</div>
        </div>
      </div>
    </main>
  </div>
</template>

<script>
export default {
  name: "App",
 }
</script>

<style>

</style>
