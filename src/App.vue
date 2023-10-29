<script>
  import Navbar from  '../src/components/Navbar.vue'
  import Projects from  '../src/components/Projects.vue'
  import Technologies from  '../src/components/Technologies.vue'
  import About from  '../src/components/About.vue'
  import MainInfo from  '../src/components/MainInfo.vue'

  export default {
    components: {Navbar, Projects, Technologies, About, MainInfo}
  }
</script>

<template>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@500&display=swap')" rel="stylesheet">
  <div class="px-24 py-6">
  <Navbar />
  <MainInfo />
  <Projects />
  <Technologies />
  <About />
</div>
</template>

<style scoped>

</style>
