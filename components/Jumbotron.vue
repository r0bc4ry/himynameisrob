<template>
  <b-jumbotron fluid class="text-center text-light">
    <template slot="header">
      Rob Cary
    </template>
    <p class="lead text-white-50 mb-5">Full Stack Developer</p>
    <b-button
      size="lg"
      variant="secondary"
      squared
      href="mailto:contact@himynameisrob.com"
    >
      <i class="fas fa-comments-dollar"></i> Hire Me
    </b-button>
  </b-jumbotron>
</template>

<script>
export default {
  name: 'Jumbotron'
}
</script>

<style scoped lang="scss">
.jumbotron {
  background-image: linear-gradient(
      -45deg,
      rgba(242, 15, 121, 0.5) 0%,
      rgba(5, 151, 242, 0.5) 100%
    ),
    url('/img/jumbotron.jpg');
  background-attachment: fixed;
  background-position: center;
  background-repeat: no-repeat;
  background-size: cover;
  padding-top: 15rem;
  padding-bottom: 15rem;
  margin-bottom: 5rem;

  h1,
  p {
    text-shadow: 0 3px 7px rgba(0, 0, 0, 0.35);
  }
  .btn {
    box-shadow: 0 3px 7px rgba(0, 0, 0, 0.35);
  }
}
</style>
