<script lang="ts">
  import Header from './lib/Header.svelte'
  import Hero from './lib/Hero.svelte'
  import About from './lib/About.svelte'
  import Events from './lib/Events.svelte'
  import Footer from './lib/Footer.svelte'
  import Mentor from './lib/mentor.svelte'
  import Sponsor from './lib/SponsorUs.svelte'

  // Simple routing: track the current page
  let page = 'home';

  // Listen for navigation events from Footer
  function navigate(newPage: string) {
    page = newPage;
    window.scrollTo(0, 0);
  }
</script>

<main>
  <Header />

  {#if page === 'home'}
    <Hero />
    <About />
    <Events />
  {:else if page === 'mentor'}
    <Mentor />
  {:else if page === 'sponsor'}
    <Sponsor />
  {/if}

  <Footer on:navigate={e => navigate(e.detail)} />
</main>

<style>
  main {
    
  }
</style>
