<script setup></script>

<template>
  <h1>Learn Mahjong, The Chinese Way!</h1>
  <div class="row">
    <div class="col-6">
      <p>
        Learn how to play Mahjong, the Chinese way. Specifically how it is played in Hong Kong. You
        can learn the rules, the scoring, and the strategies of the game. Later, you'll be able to
        play the game with other players or against the computer to practice your skills.
      </p>

      <p>
        Mahjong is a game of skill, strategy, and luck. There are many variations, played with
        different rules and different tiles. The most popular version is
        <i>Old Hong Kong Mahjong</i>, which can be played here. A short overview of the other
        popular variations is also available.
      </p>

      <div>
        <button class="btn btn-outline-dark">
          <router-link :to="{ name: 'rules' }" class="nav-link" active-class="active"
            >Rules</router-link
          >
        </button>
      </div>
    </div>

    <div class="col-6">
      <p>
        Mahjong is played and loved by millions of people around the world, mostly in Chinese
        diasporas. It's importance in Chinese culture is so great that it's considered one of the
        four great inventions of China.
      </p>

      <p>
        Players can also read about the history of Mahjong, its cultural significance, and its
        impact on Chinese society. The tiles used here can be switched to display Chinese characters
        or their English translations and Pinyin pronunciations for beginners.
        <br />
        Please feel free to immerse yourself in this entertaining part of Chinese culture.
      </p>

      <div>
        <button class="btn btn-outline-dark">
          <router-link :to="{ name: 'history' }" class="nav-link" active-class="active"
            >History & Culture</router-link
          >
        </button>
      </div>
    </div>
  </div>

  <div class="row">
    <div class="col-12 text-center">
      <h1>加油！</h1>
    </div>
  </div>
</template>

<style scoped>
h1 {
  text-align: center;
  margin-top: 2rem;
}

.row {
  margin-top: 2rem;
}

.btn {
  margin-top: 1rem;
}
</style>
