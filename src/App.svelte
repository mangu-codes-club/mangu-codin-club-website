<script lang="ts">
  import Header from './lib/Header.svelte'
  import Hero from './lib/Hero.svelte'
  import About from './lib/About.svelte'
  import Events from './lib/Events.svelte'
  import Footer from './lib/Footer.svelte'
  import Mentor from './lib/mentor.svelte'
  import Sponsor from './lib/SponsorUs.svelte'
</script>

<main>
  <Header />
  <Hero />
  <About />
  <Events />
  <Footer />
  <Mentor />
  <Sponsor />
</main>

<style>
  main {
    min-height: 100vh;
    display: flex;
    flex-direction: column;
  }
</style>
