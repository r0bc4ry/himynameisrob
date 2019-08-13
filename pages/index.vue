<template>
  <div>
    <Navbar></Navbar>
    <Jumbotron></Jumbotron>
    <b-container>
      <section>
        <b-row class="align-items-center mb-5">
          <b-col md="7" order="2" order-md="1">
            <h2>I'm a software engineer based in Washington, D.C.</h2>
            <p class="lead">
              I'm a full-stack web developer with seven years of professional
              experience. I have developed, launched, and maintained multiple
              projects for companies both large and small. I'm currently working
              as a full-time freelancer and part-time video game developer.
              <br /><br />
              When I'm not coding, you can find me grilling, playing board
              games, or outside running.
            </p>
          </b-col>
          <b-col
            cols="8"
            offset="2"
            md="5"
            offset-md="0"
            order="1"
            order-md="2"
            class="text-center"
          >
            <b-img src="/img/featurette-1.png" fluid />
          </b-col>
        </b-row>
      </section>
      <hr />
      <section>
        <b-row class="align-items-center mb-5">
          <b-col cols="8" offset="2" md="5" offset-md="0" class="text-center">
            <b-img src="/img/featurette-2.png" fluid />
          </b-col>
          <b-col md="7">
            <h2>Fast. Responsive. Intuitive.</h2>
            <p class="lead">
              I'm passionate about building excellent software that improves the
              lives of my clients and their users. I have experience in web
              development, database/server management, DevOps, graphic design,
              and video game development.
              <br /><br />
              I enjoy creating simple, beautiful solutions to complex problems.
            </p>
          </b-col>
        </b-row>
      </section>
      <hr />
      <Technologies></Technologies>
      <hr />
      <EmploymentHistory></EmploymentHistory>
      <hr />
      <section>
        <b-row class="justify-content-center align-items-center">
          <b-col cols="12 mb-3" class="d-block d-md-none text-center">
            <h4 class="text-primary">Want to work together?</h4>
            <h4>Let's chat and create something great.</h4>
          </b-col>
          <b-col cols="auto" class="d-none d-md-block">
            <h4 class="text-primary">Want to work together?</h4>
            <h4>Let's chat and create something great.</h4>
          </b-col>
          <b-col cols="1"></b-col>
          <b-col cols="auto">
            <b-button
              size="lg"
              variant="primary"
              squared
              href="mailto:r0bc4ry@gmail.com"
            >
              Contact Me
            </b-button>
          </b-col>
        </b-row>
      </section>
    </b-container>
    <Footer></Footer>
  </div>
</template>

<script>
import EmploymentHistory from '../components/EmploymentHistory.vue'
import Footer from '../components/Footer.vue'
import Jumbotron from '../components/Jumbotron.vue'
import Navbar from '../components/Navbar.vue'
import Technologies from '../components/Technologies.vue'

export default {
  components: { EmploymentHistory, Footer, Jumbotron, Navbar, Technologies }
}
</script>

<style lang="scss">
body {
  margin-top: -56px;
}
hr {
  border-top-color: #f2f2f2;
  margin: 5rem 0;
}
section {
  p.lead {
    color: #bfbfbf;
  }
  &:last-of-type {
    margin-bottom: 5rem;
  }
}
.btn.btn-primary {
  color: #fff;
}
</style>
