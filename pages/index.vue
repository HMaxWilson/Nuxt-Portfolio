<template>
  <Navigation />

  <Hero />
  <Portfolio />
  <Contact />

  <Footer />
</template>

<script setup lang="ts">
    import Navigation from "/components/Navigation.vue";
    import Footer from "/components/Footer.vue";
    import Hero from "/components/content/Hero.vue";
    import Portfolio from "/components/content/Portfolio.vue";
    import Contact from "/components/content/Contact.vue";
</script>