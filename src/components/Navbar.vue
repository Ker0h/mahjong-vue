<script setup></script>

<template>
  <header>
    <nav class="navbar fixed-top navbar-expand-lg navbar-light bg-light">
      <RouterLink to="/" class="navbar-brand">
        <img
          src="/src/assets/images/logo.png"
          alt="Mahjong Logo"
          width="50"
          height="50"
          class="d-inline-block align-top"
        />
      </RouterLink>
      <RouterLink to="/" class="navbar-brand">Learn Mahjong</RouterLink>
      <button
        class="navbar-toggler collapsed"
        type="button"
        data-toggle="collapse"
        data-target="#navbar"
        aria-controls="navbar"
        aria-expanded="false"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div id="navbar" class="navbar-collapse collapse">
        <ul class="nav navbar-nav navbar-right">
          <li>
            <router-link :to="{ name: 'tiles' }" class="nav-link" active-class="active"
              >Tiles</router-link
            >
          </li>
          <li>
            <router-link :to="{ name: 'rules' }" class="nav-link" active-class="active"
              >Rules</router-link
            >
          </li>

          <li>
            <router-link :to="{ name: 'scoring' }" class="nav-link" active-class="active"
              >Scoring</router-link
            >
          </li>

          <li>
            <router-link :to="{ name: 'history' }" class="nav-link" active-class="active"
              >History & Culture</router-link
            >
          </li>
        </ul>
      </div>
    </nav>
  </header>
</template>

<style scoped>
header {
  margin-bottom: 100px;
}
</style>
