<script lang="ts">
  // filepath: c:\Users\kenka\Desktop\coding-club\coding-club-web\src\App.svelte
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
      min-height: 100vh;
      width: 100%;
      box-sizing: border-box;
      padding: 0;
      margin: 0;
      display: flex;
      flex-direction: column;
      background: #f7fafd;
    }
  
    @media (max-width: 900px) {
      main {
        padding: 0 1rem;
      }
    }
  
    @media (max-width: 600px) {
      main {
        padding: 0 0.5rem;
      }
    }
  </style> 