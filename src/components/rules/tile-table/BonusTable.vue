<script setup></script>

<template>
  <table>
    <tbody>
      <tr>
        <th colspan="2" rowspan="3">Bonus</th>
        <th colspan="4">Seasons</th>
        <td rowspan="6"></td>
        <th colspan="4">Flowers</th>
      </tr>
      <tr>
        <th>Spring</th>
        <th>Summer</th>
        <th>Autumn</th>
        <th>Winter</th>
        <th>Plum</th>
        <th>Orchid</th>
        <th>Chrysanthemum</th>
        <th>Bamboo</th>
      </tr>
      <tr>
        <td>
          <span><img src="/src/assets/images/tile-art/spring.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/summer.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/autumn.svg" /></span>
        </td>
        <td>
          <span><img src="/src/assets/images/tile-art/winter.svg" /></span>
        </td>
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
