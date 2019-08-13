<template>
  <footer class="bg-light text-center py-5">
    <b-container>
      <p>
        Built with <i class="fas fa-heart text-secondary"></i> and
        <a href="https://nuxtjs.org/" target="_blank">Nuxt.js</a>. View the
        source code on
        <a href="https://github.com/r0bc4ry/himynameisrob" target="_blank"
          >GitHub</a
        >.
      </p>
      <p><a href="#" @click="scrollToTop">Back to Top</a></p>
    </b-container>
  </footer>
</template>

<script>
export default {
  name: 'Footer',
  methods: {
    scrollToTop: (event) => {
      window.scrollTo(0, 0)
    }
  }
}
</script>

<style scoped>
p:last-child {
  margin-bottom: 0;
}
</style>
