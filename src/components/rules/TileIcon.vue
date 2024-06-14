<script setup>
// Import all bamboo tiles
import Bamboo1 from '/src/tile-art/bamboo1.svg'
import Bamboo2 from '/src/tile-art/bamboo2.svg'
import Bamboo3 from '/src/tile-art/bamboo3.svg'
import Bamboo4 from '/src/tile-art/bamboo4.svg'
import Bamboo5 from '/src/tile-art/bamboo5.svg'
import Bamboo6 from '/src/tile-art/bamboo6.svg'
import Bamboo7 from '/src/tile-art/bamboo7.svg'
import Bamboo8 from '/src/tile-art/bamboo8.svg'
import Bamboo9 from '/src/tile-art/bamboo9.svg'

// Import all character tiles
import Character1 from '/src/tile-art/character1.svg'
import Character2 from '/src/tile-art/character2.svg'
import Character3 from '/src/tile-art/character3.svg'
import Character4 from '/src/tile-art/character4.svg'
import Character5 from '/src/tile-art/character5.svg'
import Character6 from '/src/tile-art/character6.svg'
import Character7 from '/src/tile-art/character7.svg'
import Character8 from '/src/tile-art/character8.svg'
import Character9 from '/src/tile-art/character9.svg'

// Import all circle tiles
import Dot1 from '/src/tile-art/dot1.svg'
import Dot2 from '/src/tile-art/dot2.svg'
import Dot3 from '/src/tile-art/dot3.svg'
import Dot4 from '/src/tile-art/dot4.svg'
import Dot5 from '/src/tile-art/dot5.svg'
import Dot6 from '/src/tile-art/dot6.svg'
import Dot7 from '/src/tile-art/dot7.svg'
import Dot8 from '/src/tile-art/dot8.svg'
import Dot9 from '/src/tile-art/dot9.svg'

// Import all wind tiles
import East from '/src/tile-art/east.svg'
import South from '/src/tile-art/south.svg'
import West from '/src/tile-art/west.svg'
import North from '/src/tile-art/north.svg'

// Import all dragon tiles
import DragonRed from '/src/tile-art/red-dragon.svg'
import DragonGreen from '/src/tile-art/green-dragon.svg'
import DragonWhite from '/src/tile-art/white-dragon.svg'

// Import all flower tiles
import Plum from '/src/tile-art/plum.svg'
import Orchid from '/src/tile-art/orchid.svg'
import Chrysanthemum from '/src/tile-art/chrysanthemum.svg'
import Bamboo from '/src/tile-art/bamboo.svg'

// Import all season tiles
import Spring from '/src/tile-art/spring.svg'
import Summer from '/src/tile-art/summer.svg'
import Autumn from '/src/tile-art/autumn.svg'
import Winter from '/src/tile-art/winter.svg'

// Create a map of tile names to their images
const tileImages = {
  bamboo1: Bamboo1,
  bamboo2: Bamboo2,
  bamboo3: Bamboo3,
  bamboo4: Bamboo4,
  bamboo5: Bamboo5,
  bamboo6: Bamboo6,
  bamboo7: Bamboo7,
  bamboo8: Bamboo8,
  bamboo9: Bamboo9,
  character1: Character1,
  character2: Character2,
  character3: Character3,
  character4: Character4,
  character5: Character5,
  character6: Character6,
  character7: Character7,
  character8: Character8,
  character9: Character9,
  dot1: Dot1,
  dot2: Dot2,
  dot3: Dot3,
  dot4: Dot4,
  dot5: Dot5,
  dot6: Dot6,
  dot7: Dot7,
  dot8: Dot8,
  dot9: Dot9,
  east: East,
  south: South,
  west: West,
  north: North,
  'red-dragon': DragonRed,
  'green-dragon': DragonGreen,
  'white-dragon': DragonWhite,
  plum: Plum,
  orchid: Orchid,
  chrysanthemum: Chrysanthemum,
  bamboo: Bamboo,
  spring: Spring,
  summer: Summer,
  autumn: Autumn,
  winter: Winter
}
</script>

<template>
  <img :src="tileImages[tileName]" alt="Tile" />
</template>

<style scoped>
img {
  width: 100%;
  height: auto;
}
</style>
