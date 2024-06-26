<script setup></script>

<template>
  <table>
    <tbody>
      <tr>
        <th colspan="2" rowspan="3">Honours</th>
        <th colspan="4">Winds</th>
        <td rowspan="6"></td>
        <th colspan="3">Dragons</th>
      </tr>
      <tr>
        <th>East</th>
        <th>South</th>
        <th>West</th>
        <th>North</th>
        <th>Red</th>
        <th>Green</th>
        <th>White</th>
      </tr>
      <tr>
        <td>
          <span><img src="/src/assets/images/tile-art/east.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/south.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/west.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/north.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/red-dragon.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/green-dragon.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/white-dragon.svg" /></span>
        </td>
      </tr>
    </tbody>
  </table>
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
</style>
