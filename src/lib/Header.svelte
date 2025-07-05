<script lang="ts">
  let menuOpen = false;
  
  function toggleMenu() {
    menuOpen = !menuOpen;
  }
</script>

<header class="header">
  <div class="container">
    <div class="logo">
      <h2>👨🏼‍💻Mangu Coding Club</h2>
    </div>
    
    <nav class="nav" class:open={menuOpen}>
      <a href="#home">Home</a>
      <a href="#about">About</a>
      <a href="#events">Events</a>
      <a href="#contact">Contact</a>
    </nav>
    
    <button class="menu-toggle" on:click={toggleMenu}>
      <span></span>
      <span></span>
      <span></span>
    </button>
  </div>
</header>

<style>
  .header {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem 0;
    position: sticky;
    top: 0;
    z-index: 100;
    box-shadow: 0 2px 10px rgba(0,0,0,0.1);
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
    display: flex;
    justify-content: space-between;
    align-items: center;
  }
  
  .logo h2 {
    margin: 0;
    font-size: 1.5rem;
    font-weight: bold;
  }
  
  .nav {
    display: flex;
    gap: 2rem;
  }
  
  .nav a {
    color: white;
    text-decoration: none;
    font-weight: 500;
    transition: opacity 0.3s ease;
  }
  
  .nav a:hover {
    opacity: 0.8;
  }
  
  .menu-toggle {
    display: none;
    flex-direction: column;
    background: none;
    border: none;
    cursor: pointer;
    padding: 0;
  }
  
  .menu-toggle span {
    width: 25px;
    height: 3px;
    background: white;
    margin: 3px 0;
    transition: 0.3s;
  }
  
  @media (max-width: 768px) {
    .nav {
      position: absolute;
      top: 100%;
      left: 0;
      right: 0;
      background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
      flex-direction: column;
      padding: 1rem 2rem;
      transform: translateY(-100%);
      opacity: 0;
      visibility: hidden;
      transition: all 0.3s ease;
    }
    
    .nav.open {
      transform: translateY(0);
      opacity: 1;
      visibility: visible;
    }
    
    .menu-toggle {
      display: flex;
    }
  }
</style>
