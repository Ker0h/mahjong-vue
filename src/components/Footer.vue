<script setup>
import { FontAwesomeIcon } from '@fortawesome/vue-fontawesome'
import { faGithub } from '@fortawesome/free-brands-svg-icons'
</script>

<template>
  <div class="spacing"></div>
  <footer>
    <div class="footer bg-light">
      <div class="container">
        <div class="row">
          <div class="col-12">
            <h5>
              Created by
              <a href="https://github.com/Ker0h" target="_blank" rel="noopener noreferrer">
                <FontAwesomeIcon :icon="faGithub" />
                Ker0h
              </a>
            </h5>
          </div>
        </div>
      </div>
    </div>
  </footer>
</template>

<style scoped>
.spacing {
  margin-bottom: 100px;
}
.footer {
  padding: 20px 0;
  text-align: center;
}
.footer a {
  color: #343a40;
  text-decoration: none;
}
.footer a:hover {
  color: #007bff;
}
.footer h5 {
  margin-bottom: 0;
}
.footer svg {
  margin-right: 5px;
}
</style>
