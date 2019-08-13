<template>
  <b-navbar type="dark" variant="transparent">
    <b-navbar-nav class="ml-auto">
      <b-nav-item href="https://github.com/r0bc4ry" target="_blank">
        <i class="fab fa-github"></i>
      </b-nav-item>
      <b-nav-item href="https://twitter.com/r0bc4ry" target="_blank">
        <i class="fab fa-twitter"></i>
      </b-nav-item>
      <b-nav-item href="mailto:r0bc4ry@gmail.com">
        <i class="fas fa-envelope"></i>
      </b-nav-item>
    </b-navbar-nav>
  </b-navbar>
</template>

<script>
export default {
  name: 'Navbar'
}
</script>

<style scoped>
.navbar {
  height: 56px;
  transform: translateY(56px);
  z-index: 128;
}
</style>
