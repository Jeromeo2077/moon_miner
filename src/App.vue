// JS
<script setup>
import { computed, ref } from 'vue'
import { AppState } from './AppState.js'

function mineCheese(){
  
}

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

    <main class="container-fluid">
    <section class="row m-3">
      <div class="col d-flex justify-content-center">

        <button @click="mineCheese()" class="buttonMoonImage" style="width:13em;height:13em;"></button>

      </div>
    </section>

    <footer class="container-fluid">
    <section class="row">

      <div class="col d-flex justify-content-center">

        <div>
          <span class="badge rounded-pill text-bg-warning cheeseTotal">Cheese Total: {{  }} </span>
          <span class="badge rounded-pill text-bg-warning cheeseClick">Cheese per click: {{  }} </span>
          <span class="badge rounded-pill text-bg-warning cheesePerTurn">Cheese per turn: {{  }} </span>
        </div>

      </div>

    </section>
    </footer>

  </main>

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

.buttonMoonImage {
    background-image: url(./src/assets/img/moon_background.png);
    background-size: cover;
    background-position: center;
  }

</style>