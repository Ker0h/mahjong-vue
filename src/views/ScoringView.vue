<script setup>
import ScoringTableComponent from '@/components/rules/ScoringTableComponent.vue'
</script>

<template>
  <div class="row">
    <div class="col-12">
      <h1>Scoring</h1>

      <div>
        <p>
          In the world of Mahjong there are many different scoring systems, depending on the variant
          being played, regional differences etc.
          <br />
          This is why when you play a game of Mahjong, you should always agree on the scoring system
          beforehand.
        </p>

        <p>
          Here we'll mostly cover the scoring system used in Hong Kong-style Mahjong, also known as
          the Cantonese scoring system, which is the most prevalent one.
        </p>

        <h2>Fān (翻)</h2>
        <p>
          The basic unit of scoring in Mahjong is the fān (翻). A fān is a doubling of points, which
          is why it is sometimes translated as "doubles". The more fān you have, the more points you
          get.
        </p>
        <p>
          The number of fān you have is determined by the combination of tiles in your hand. The
          more difficult the combination is to get, the more fān it is worth.
        </p>
        <p>Here are some examples of combinations and their fān value:</p>
      </div>

      <ScoringTableComponent />

      <div class="spacing"></div>

      <h2>Special Hands</h2>
      <div>
        <p>
          In addition to the basic sets, there are also special hands that are worth more points.
          These are hands that are difficult to get, and are therefore worth more points.
        </p>
        <p>
          There are too many special hands to list them all here, but some examples include the
          Seven Pairs, Big Four Winds, and the Thirteen Orphans.
        </p>
        <p>
          Special hands are worth a fixed number of fān plus the amount of fān of it's individual
          components as listed above.
        </p>
      </div>
    </div>
  </div>
</template>

<style scoped></style>
