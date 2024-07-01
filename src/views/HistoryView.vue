<script setup></script>

<template>
  <div class="row">
    <div class="col-12">
      <h1>History</h1>
      <div>
        <p>
          The history of Mahjong is relatively short, only being developed towards the end of the
          Qing Dynasty in the mid-1800's. Mahjong was originally called máquè (麻雀) which means
          "sparrow", in reference to the clacking sound the tiles make when shuffled, which sounds
          like the chirping of birds. The game was developed by a group of scholars and military
          officers who were looking for a way to pass the time. It quickly spread throughout China
          and became popular with the general public, mostly as a form of gambling.
          <br />
          The game was originally played with cards, but was later adapted to use tiles. The game
          was further refined in the early 20th century by a group of businessmen in Shanghai
        </p>
        <p>
          It's popularity continued to grow and by the early 1900's, Mahjong had become a national
          pastime. The influence of Mahjong on Chinese culture is so great it is often called one of
          the "Four Great Inventions of China".
        </p>
      </div>
    </div>

    <h2>Spread to the West</h2>
    <div class="col-8">
      <p>
        Mahjong didn't only become popular in China, it also became well known in the West. The game
        was first introduced to the American public in the 1920's by a man named Joseph P. Babcock,
        who as the story goes discovered the game while sailing on a ship across the Yangtze River.
      </p>
      <p>
        Babcock was so taken with the game that he decided to bring it back to the United States and
        introduce it to the American public. He made a few changes to the game, such as adding joker
        tiles and changing the scoring system, to make it more appealing to Western players. The
        game became so popular that Mahjong related exports helped to create new jobs and otherwise
        boost the economy of the newly established Republic of China.
      </p>
    </div>

    <div class="col-4">
      <span><img src="/src/assets/images/rules_of_mah_jongg.jpg" /></span>
    </div>

    <h2>Mahjong under Communism</h2>
    <div class="col-12">
      <p>
        The growth of Mahjong in China however, hit a roadblock, when in 1949 Chairman Mao Zedong
        declared the game illegal on grounds it promoted gambling. Since he thought that a worker
        should spend their money on his family and not on gambling, all forms of gambling were
        banned in China, which they still are today.
      </p>
      <p>
        The other main reson Mahjong was banned however, was because of it's relation to culture
        under Imperial rule. So it was that many Mahjong related paraphernelia were repossesed or
        destroyed during "The Cultural Revolution".
        <br />
        After the rule of Mao ended, Mahjong started to regain it's popularity again, as laws grew
        slightly more lenient.
      </p>
    </div>

    <hr />

    <div class="col-12">
      <p>
        Aside from an interesting history, Mahjong also has great cultural significance to China.
        With many references to Confucianism, superstitions surrounding it, and its very own
        gambling culture.
      </p>
      <button class="btn btn-outline-dark">
        <router-link :to="{ name: 'culture' }" class="nav-link" active-class="active"
          >Culture</router-link
        >
      </button>
    </div>
  </div>
</template>

<style scoped>
img {
  width: 60%;
}
</style>
