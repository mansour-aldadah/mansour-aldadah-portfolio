<template>
  <div id="app">
    <Navigation />
    <SocialSidebar />
    <EmailSidebar />
    <main>
      <Hero />
      <About />
      <Skills />
      <Projects />
      <Contact />
    </main>
  </div>
</template>

<script>
import Navigation from './components/Navigation.vue'
import SocialSidebar from './components/SocialSidebar.vue'
import EmailSidebar from './components/EmailSidebar.vue'
import Hero from './components/Hero.vue'
import About from './components/About.vue'
import Skills from './components/Skills.vue'
import Projects from './components/Projects.vue'
import Contact from './components/Contact.vue'

export default {
  name: 'App',
  components: {
    Navigation,
    SocialSidebar,
    EmailSidebar,
    Hero,
    About,
    Skills,
    Projects,
    Contact
  }
}
</script>

<style>
body {
  counter-reset: section;
}

main {
  margin: 0 auto;
  width: 100%;
  max-width: 1600px;
  min-height: 100vh;
  padding: 0 150px;
}

@media (max-width: 1080px) {
  main {
    padding: 0 100px;
  }
}

@media (max-width: 768px) {
  main {
    padding: 0 50px;
  }
}

@media (max-width: 480px) {
  main {
    padding: 0 25px;
  }
}
</style>