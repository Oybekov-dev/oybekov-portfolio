<template>
  <div>
    <Navbar />
    <About />
    <Projects />
    <Skills />
    <Contact />
    <Footer />
  </div>
</template>

<script setup>
import Navbar from './components/Navbar.vue'
import About from './components/About.vue'
import Projects from './components/Projects.vue'
import Skills from './components/Skills.vue'
import Contact from './components/Contact.vue'
import Footer from './components/Footer.vue'
</script>

<style>
/* Global Styles */
* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

body {
  font-family: 'Poppins', sans-serif;
  background-color: #f8f8f8;
  color: #333;
  line-height: 1.6;
  scroll-behavior: smooth;
}

.container {
  width: 85%;
  margin: 0 auto;
  max-width: 1200px;
}
</style>
