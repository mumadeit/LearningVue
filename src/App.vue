<script setup>
import { RouterLink, RouterView } from 'vue-router'
// import bootstrap from 'bootstrap'

</script>

<template>
  <header class="p-3 text-bg-light border">
    <div class="container">
      <div class="d-flex flex-wrap align-items-center justify-content-center justify-content-lg-start">
        <a href="/" class="d-flex align-items-center mb-2 mb-lg-0 text-white text-decoration-none">
          <svg class="bi me-2" width="40" height="32" role="img" aria-label="Bootstrap">
            <use xlink:href="#bootstrap"></use>
          </svg>
        </a>

        <ul class="nav col-12 col-lg-auto me-lg-auto mb-2 justify-content-center mb-md-0">
          <RouterLink class="nav-link text-dark px-2" to="/">Home</RouterLink>
          <RouterLink class="nav-link text-dark px-2" to="/about">About</RouterLink>
        </ul>



        <div class="text-end">
          <button type="button" class="btn-main me-2">Let's Talk</button>
          <button type="button" class="btn-main">Call me</button>
        </div>
      </div>
    </div>
  </header>

  <RouterView />
</template>

<style scoped></style>
