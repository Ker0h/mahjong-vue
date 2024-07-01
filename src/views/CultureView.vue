<script setup></script>

<template>
  <div class="row">
    <div class="col-12">
      <h1>Culture</h1>
      <div>
        <p>
          Not only does Mahjong have an interesting history, it's also very important to Chinese
          culture. The game contains some references to Confucianism, one of the three main
          religions of China. There are also many superstitions surrounding the game. Lastly there
          is a whole gambling culture surrounding Mahjong, which is still very much alive today.
        </p>
      </div>

      <div class="spacing"></div>

      <h2>The Four Gentlemen</h2>
      <div>
        <p>
          Of the different tiles that are used in Mahjong, you might have seen the ones knows as
          Season or Flower tiles. The flowers on these tiles are the plum, the orchid, the bamboo
          and the chrysenthemum.
          <br />
          These flowers are also known as the "Four Gentlemen" in Confucianism and are often seen in
          many Classical Chinese art, where they depict the four seasons.
        </p>

        <table>
          <tr>
            <th>Plum</th>
            <th>Orchid</th>
            <th>Bamboo</th>
            <th>Chrysanthemum</th>
          </tr>
          <tr>
            <td>
              <span><img src="/src/assets/images/tile-art/plum.svg" /></span>
            </td>
            <td>
              <span><img src="/src/assets/images/tile-art/orchid.svg" /></span>
            </td>
            <td>
              <span><img src="/src/assets/images/tile-art/chrysanthemum.svg" /></span>
            </td>
            <td>
              <span><img src="/src/assets/images/tile-art/bamboo.svg" /></span>
            </td>
          </tr>
        </table>

        <p>
          These four flowers are know as the "Four Gentlemen" or the "Four Nobles" because of the
          importance of the nobility in Confucianism. Each one of these plants represents a noble
          virtue and is associated with a season.
        </p>

        <p>
          The plum for example, represents inner beauty and humility because, while it isn't very
          impressive, the way it blossoms in winter <i>is</i>.
        </p>
        <p>
          The orchid on the other hand, represents nobility and humanity, because it's a very
          beautiful flower that blooms in spring.
        </p>
        <p>
          The bamboo represents integrity and modesty, because it's a very strong plant that bends
          with the wind. It bends, but does not give in.
        </p>
        <p>
          Lastly, the chrysanthemum blooms in autumn and signals the coming of winter. As such it
          represents withstanding hardships and the ability to survive.
        </p>

        <div>
          <span><img class="painting" src="/src/assets/images/tao-yuanming.jpg" /></span>
          <sub>
            <a href="https://en.wikipedia.org/wiki/Tao_Yuanming" target="_blank">Tao Yuanming</a>
            (365-427) was a Chinese poet who was known for his love of the chrysenthemums. This is a
            painting by Zhao Lingran aptly titled: "Tao Yuanming Admiring Chrysanthemums".
          </sub>
        </div>
      </div>

      <div class="spacing"></div>

      <h2>Superstitious Beliefs</h2>
      <div>
        <p>
          Considering playing Mahjong requires both strategy and luck, it is not surprising there
          are a few superstitions surrounding the game. For example, one should not tap someone on
          the shoulder during the game, as this might disrupt their winning streak, even across
          multiple rounds. On the contrary, it is believed that someone can 'wash away' bad luck. So
          a player can often be seen visiting the toilet after a series of losses, just to wash
          their hands. Also, it is considered bad luck to have books on or near a Mahjong table as
          the words for 'book' (書/Shū) and 'to lose' (失去/Shīqù) sound somewhat similiar in
          Chinese. Lastly, in a similiar vein, one should never discard four 'West' tiles after one
          another, as the words for 'four' (四/Sì), 'West' (西/Xī) and 'death' (死/Sǐ) sound the
          same in Chinese.
        </p>
      </div>
    </div>

    <div class="spacing"></div>

    <h2>Gambling Culture</h2>
    <div class="col-8">
      <p>
        Even though currently the Chinese government is more lenient towards gambling than it was
        during the time of Mao, it is still illegal. That's why Chinese citizens will often play
        Mahjong for money in secret, or in a more public setting, but without money involved.
        Visiting a Mahjong parlor in the 'Special Administrative Regions' (SAR) of China, like Macau
        or Hong Kong, is also quite popular.
      </p>
      <p>
        One of the reasons Mahjong is still popular today is because it's a very social game. People
        sit across from one another and the scrambling and dividing of tiles takes significantly
        longer than with cards during a card game, allowing for conversations to more easily come
        up.
      </p>
    </div>
    <div class="col-4">
      <span><img class="parlor" src="/src/assets/images/watercolor-mahjong-madness.jpg" /></span>
    </div>
    <div class="spacing"></div>

    <div class="col-12">
      <p>
        Most importantly however, is that gambling as a whole is just an unbeatable concept in
        China. The prospect of relatively quick and 'easy' riches is just too tempting for many
        people to resist. And the gathering of wealth and as such, well being, is one of the most
        important parts of modern Chinese culture.
        <br />
        As they say during New Years: "恭喜發財！" (Gōngxǐ fācái!) which means "Congratulations and
        be prosperous!", or more literally: "Let's get rich and be prosperous!".
      </p>
    </div>
  </div>
</template>

<style scoped>
table {
  width: 100%;
  border-collapse: collapse;
}
th {
  text-align: left;
  padding: 0.5rem;
}
td {
  padding: 0.5rem;
}
span {
  display: block;
  width: 100%;
  height: 100%;
  padding: 0.5rem;
}
img {
  width: 100px;
  height: auto;
}
.painting {
  width: 100%;
}
.parlor {
  width: 80%;
}
</style>
