<script setup></script>

<template>
  <h2>Gameplay</h2>
  <div>
    <p>The players take turns, counter clockwise, to perform one of six actions:</p>

    <ul>
      <li>Draw a tile from the wall (摸牌 <i>Mō pái</i>)</li>
      <li>Form a Pong (碰 <i>Pèng</i>)</li>
      <li>Form a Chow (吃 <i>Chī</i>)</li>
      <li>Form a Kong (槓 <i>Gàng</i>)</li>
      <li>Draw and replace a flower tile (花 <i>Huā</i>)</li>
      <li>Declare a win (和/食 <i>Hú/Shí</i>)</li>
    </ul>
  </div>

  <h2>Building a winning hand</h2>
  <div>
    <p>A winning hand consists of four sets and a pair. A set can be a Pong, a Kong, or a Chow.</p>

    <h3>Drawing a tile</h3>
    <p>
      A player must draw a tile from the start of the wall and add it to their hand. <br />
      The player must then choose a tile to discard from their hand.
    </p>

    <h3>Pong</h3>
    <p>
      A Pong is a set of three identical tiles. A player can form a Pong by taking a tile from the
      wall or by forming one with a tile that is being discarded by another player. <br />
      A Pong that is formed this way must be shown to the other players, whilst a Pong that is
      formed by taking a tile from the wall does not need to be shown.
    </p>

    <h3>Chow</h3>
    <p>
      A Chow is a set of three consecutive tiles in the same suit. A player can form a Chow by
      taking a tile from the wall or by forming one with a tile that is being discarded by another
      player.
      <br />
      Unlike with a Pong, the player that's discarding the needed tile must be seated to the left of
      the player that's declaring the Chow. <br />
      If a tile is desired by multiple players, a Pong will take precedence over a Chow, otherwise
      the player closest to the discarder gets the tile. <br />
      A Chow that is formed this way must be shown to the other players, whilst a Chow that is
      formed by taking a tile from the wall does not need to be shown.
    </p>

    <h3>Kong</h3>
    <p>
      A Kong is a set of four consecutive tiles in the same suit. A player can form a Kong by taking
      a tile from the wall or by forming one with a tile that is being discarded by another player.
      <br />
      A Kong that is formed this way must be shown to the other players, whilst a Kong that is
      formed by taking a tile from the wall does not need to be shown. <br />
      Unlike with a Pong or a Chow, a Kong allows the player to draw an extra tile from the end of
      the wall.
    </p>

    <h3>Drawing a Flower tile</h3>
    <p>
      Whenever a player draws a flower tile, they can replace it with a tile from the end of the
      wall.
      <br />
      The player can then choose to keep the flower tile to possibly form a Kong or discard it.
    </p>

    <h3>Winning</h3>
    <p>
      A player can declare a win when they have a winning hand. <br />
      Aside from the four sets, a winning hand must also contain a pair. <br />
      A pair can be completed by drawing a tile from the wall or by forming one with a tile that is
      being discarded by another player. <br />
      The player must then show their winning hand to the other players and claim their win.
    </p>
  </div>
</template>

<style scoped>
h3 {
  font-size: 1.5rem;
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
