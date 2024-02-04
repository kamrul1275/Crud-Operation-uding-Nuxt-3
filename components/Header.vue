<template>
      <nav class="navbar navbar-expand-lg navbar-light bg-light">
  <div class="container">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-bs-toggle="collapse" data-bs-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarSupportedContent">
      <ul class="navbar-nav ms-auto mb-2 mb-lg-0">
        <li class="nav-item">
          <nuxt-link to="/" class="nav-link active" aria-current="page">Home</nuxt-link>
        </li>
        <li class="nav-item">
            <nuxt-link to="/product" class="nav-link active" aria-current="page">Product</nuxt-link>
        </li>
        <li class="nav-item">
            <nuxt-link to="/about" class="nav-link active" aria-current="page">About</nuxt-link>
        </li>
       
       
      </ul>
     
    </div>
  </div>
</nav>
</template>

<script setup>

</script>

<style lang="scss" scoped>

</style>