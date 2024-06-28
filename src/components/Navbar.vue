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
        class="navbar-toggler"
        type="button"
        data-toggle="collapse"
        data-target="#navbarNavDropdown"
        aria-controls="navbarNavDropdown"
        aria-expanded="false"
        aria-label="Toggle navigation"
      >
        <span class="navbar-toggler-icon"></span>
      </button>
      <div class="collapse navbar-collapse" id="navbarNavDropdown">
        <ul class="navbar-nav">
          <li class="nav-item dropdown">
            <a
              class="nav-link dropdown-toggle"
              href="tiles"
              id="navbarDropdownMenuLink"
              role="button"
              data-toggle="dropdown"
              aria-haspopup="true"
              aria-expanded="false"
            >
              Rules
            </a>
            <div class="dropdown-menu" aria-labelledby="navbarDropdownMenuLink">
              <a class="dropdown-item" href="#">Tiles</a>
              <a class="dropdown-item" href="#">Gameplay</a>
              <a class="dropdown-item" href="#">Scoring</a>
            </div>
          </li>
          <li class="nav-item">
            <a class="nav-link" href="history">History & Culture</a>
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
