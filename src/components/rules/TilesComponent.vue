<script setup>
import SuitsTable from './tile-table/SuitsTable.vue'
import HonoursTable from './tile-table/HonoursTable.vue'
import BonusTable from './tile-table/BonusTable.vue'
</script>

<template>
  <div class="row">
    <div class="col-12">
      <h1>Tiles</h1>
      <p>
        The game of Mahjong is played with a set of 144 tiles based on Chinese characters and
        symbols. Hong Kong style Mahjong however, uses a set of 136 tiles. <br />
        Any set of Mahjong tiles consists of three suits: Bamboo, Characters, and Dots. With each
        suit having tiles numbered from 1 to 9.
      </p>

      <SuitsTable />

      <p>
        There are also the Honour tiles which consist of the Wind and Dragon tiles. The Wind tiles
        are East, South, West, and North. The Dragon tiles are Red, Green, and White.
      </p>

      <HonoursTable />

      <p>
        Lastly there are the Flower tiles which are optional and are used in some variations of the
        game, including Hong Kong style Mahjong. <br />
        Flower tiles are divided into the regular Flower tiles and Season tiles. Unlike with the
        suits and Honour tiles, there are only one of each Flower tile.
      </p>

      <BonusTable />
    </div>
  </div>
</template>

<style scoped></style>
