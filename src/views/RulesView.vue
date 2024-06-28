<script setup>
import StartingComponent from '@/components/rules/StartingComponent.vue'
import GameplayComponent from '@/components/rules/GameplayComponent.vue'
</script>

<template>
  <div class="row">
    <div class="col-12">
      <StartingComponent />

      <p>Now that you know how to start a game, let's learn how to play Mahjong.</p>

      <GameplayComponent />

      <p>Finally, let's take a look at how scoring works.</p>

      <button class="btn btn-outline-dark">
        <router-link :to="{ name: 'scoring' }" class="nav-link" active-class="active"
          >Scoring</router-link
        >
      </button>
    </div>
  </div>
</template>
