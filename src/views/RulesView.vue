<template>
  <div class="row">
    <div class="col-12">
      <h1>Rules of <i>(Hong Kong style)</i> Mahjong</h1>
      <p>
        The game of Mahjong is played with a set of 144 tiles based on Chinese characters and
        symbols. The goal is to build a winning hand by drawing and discarding tiles to form sets
        and pairs, better known as <i>Melds</i> and <i>Eyes</i>. Mahjong is played by four players
        and the winner is the player with the highest score at the end.
      </p>

      <p>
        Scoring is done differently depending on the variation of Mahjong being played, and even
        within those variations there are many different scoring systems. This is why, in China,
        people tend to agree on a ruleset before they start playing.
      </p>

      <p>Let's first take a look at all the different tiles that are used in Mahjong.</p>

      <button class="btn btn-outline-dark">
        <router-link :to="{ name: 'tiles' }" class="nav-link" active-class="active"
          >Tiles</router-link
        >
      </button>
    </div>
  </div>
</template>

<style>
article {
  margin: 0 auto;
  padding: 1rem;
  max-width: 800px;
}

h2 {
  font-size: 2rem;
  margin-bottom: 1rem;
}

h3 {
  font-size: 1.5rem;
  margin-top: 1rem;
  margin-bottom: 1rem;
}

h4 {
  font-size: 1.25rem;
  margin-top: 1rem;
  margin-bottom: 1rem;
}

p {
  margin-top: 1rem;
  margin-bottom: 1rem;
}

ul {
  margin-top: 1rem;
  margin-bottom: 1rem;
}

li {
  margin-top: 0.5rem;
  margin-bottom: 0.5rem;
}
</style>
