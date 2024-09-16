// JS
<script setup>
import { computed } from 'vue'
import { AppState } from './AppState.js'


</script>


// HTML
<template>
  <body class="cheeseMinerBackground">
    
    <header class="bg-dark text-light text-center">
      <div class="container-fluid">
        <section class="row">
          <div class="col">
            <h1 class="title">Moon Miner</h1>
          </div>
        </section>
      </div>
    </header>

  </body>
</template>


// styles
<style lang="scss">
@import "./assets/scss/main.scss";

.title{
  font-weight: 400;
    font-style: normal;
    font-size: 5em;
}

    .cheeseMinerBackground {
    background-image: url(./src/assets/img/galaxy_background.png);
    min-height: 100vh;
    background-size: cover;
    background-position: center;
    font-size: 1.5em;
}

</style>