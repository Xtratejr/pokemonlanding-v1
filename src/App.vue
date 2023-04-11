<script setup>
import HelloWorld from './components/HelloWorld.vue'
import TheWelcome from './components/TheWelcome.vue'
import PokemonMagicList from './components/PokemonMagicList.vue';
</script>

<template>
  <header class="poke-header">
    <div class="poke-logo">
      <img alt="Pokemon Logo" class="" src="/img/poke-logo.png" />
    </div>
    <div class="poke-wrapper">
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
          Shop
        </span>
      </div>
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
          About Us
        </span>
      </div>
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
          Scarlet - Violet
        </span>
      </div>
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
          Scarlet
        </span>
      </div>
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
          Violet
        </span>
      </div>
      <div class="poke-item">
        <span>
          <i class="fa fa-shopping-bag" aria-hidden="true"></i>
            Pokemon Unite
        </span>
      </div>
      <!-- <HelloWorld msg="Xpress Cars Venezuela" /> -->
    </div>
    <div class="poke-nav">
      <ul>
        <li> home </li>
        <li> Pokedex </li>
        <li> Video Games & Apps </li>
        <li> Tradding Card Game </li>
        <li> Pokemon TV </li>
        <li> Play! Pokemon Events </li>
        <li> News </li>
      </ul>
    </div>
  </header> 

  <main>
    <TheWelcome />
    <PokemonMagicList title="Pokemon Magic List"/>
  </main>
</template>

<style scoped>
header {
  line-height: 1.5;
}

.logo {
  display: block;
  margin: 0 auto 2rem;
}

@media (min-width: 1024px) {
  header {
    display: flex;
    place-items: center;
    padding-right: calc(var(--section-gap) / 2);
  }

  .logo {
    margin: 0 2rem 0 0;
  }

  header .wrapper {
    display: flex;
    place-items: flex-start;
    flex-wrap: wrap;
  }
}
</style>
