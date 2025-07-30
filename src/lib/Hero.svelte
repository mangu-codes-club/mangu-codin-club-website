<section id="home" class="hero">
  <div class="container">
    <div class="hero-content">
      <h1>
        Welcome to<br />
        Mangu Coding<br />
         Club
      </h1>
      <p class="hero-subtitle">
        Where passion meets programming! <br />Join our community of developers,<br /> 
        learners, and innovators as <br />we explore the exciting <br />world of code together.
      </p>
      <div class="hero-buttons">
        <!-- <button class="btn primary">Join Us</button> -->
        <button class="btn secondary"><a href="#about">Learn More</a></button>
      </div>
    </div>
    <div class="hero-visual">
      <div class="code-block">
        <div class="code-header">
          <div class="dots">
            <span class="dot red"></span>
            <span class="dot yellow"></span>
            <span class="dot green"></span>
          </div>
          <span class="filename">mangu-club.js</span>
        </div>
        <div class="code-content">
          <pre><code>const manguClub = &#123;
  mission: "Learn, Build, Share",
  members: "Growing daily!",
  languages: [
          "JavaScript",
          "Python", 
          "Java"
     ],
  activities: [
          "Workshops",
          "Hackathons", 
          "Projects"
     ],
  
  welcome() &#123;
    console.log(
      "Welcome to Mangu Coding Club!"
      );
  &#125;
&#125;;</code></pre>
        </div>
      </div>
    </div>
  </div>
</section>

<style>
  .hero {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 6rem 0;
    min-height: 80vh;
    display: flex;
    align-items: center;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 4rem;
    align-items: center;
  }
  
  .hero-content h1 {
    font-size: 3.5rem;
    font-weight: bold;
    margin: 0 0 1.5rem 0;
    line-height: 1.2;
  }
  
  .hero-subtitle {
    font-size: 1.2rem;
    line-height: 1.6;
    margin: 0 0 2rem 0;
    opacity: 0.9;
  }
  
  .hero-buttons {
    display: flex;
    gap: 1rem;
    flex-wrap: wrap;
  }
  
  .btn {
    padding: 1rem 2rem;
    border-radius: 8px;
    font-size: 1rem;
    font-weight: 600;
    cursor: pointer;
    border: none;
    transition: all 0.3s ease;
    text-transform: uppercase;
    letter-spacing: 0.5px;
  }
  
  .btn.primary {
    background: #ff6b6b;
    color: white;
  }
  
  .btn.primary:hover {
    background: #ff5252;
    transform: translateY(-2px);
  }
  
  .btn.secondary {
    background: transparent;
    color: white;
    border: 2px solid white;
  }
  
  .btn.secondary:hover {
    background: white;
    color: #667eea;
    transform: translateY(-2px);
  }
  
  .code-block {
    background: #1e1e1e;
    border-radius: 12px;
    overflow: hidden;
    box-shadow: 0 20px 40px rgba(0,0,0,0.3);
  }
  
  .code-header {
    background: #2d2d2d;
    padding: 1rem;
    display: flex;
    align-items: center;
    gap: 1rem;
  }
  
  .dots {
    display: flex;
    gap: 0.5rem;
  }
  
  .dot {
    width: 12px;
    height: 12px;
    border-radius: 50%;
  }
  
  .dot.red { background: #ff5f56; }
  .dot.yellow { background: #ffbd2e; }
  .dot.green { background: #27ca3f; }
  
  .filename {
    color: #a0a0a0;
    font-size: 0.9rem;
  }
  
  .code-content {
    padding: 1.5rem;
  }
  
  .code-content pre {
    margin: 0;
    font-family: 'Monaco', 'Menlo', 'Ubuntu Mono', monospace;
    font-size: 0.9rem;
    line-height: 1.6;
    color: #e6e6e6;
  }
  
  .code-content code {
    color: #e6e6e6;
  }
  
  @media (max-width: 768px) {
    .hero {
      padding: 4rem 0;
    }
    
    .container {
      grid-template-columns: 1fr;
      gap: 3rem;
    }
    
    .hero-content {
      text-align: center;
    }
    
    .hero-content h1 {
      font-size: 2.5rem;
    }
    
    .hero-subtitle {
      font-size: 1.1rem;
    }
    
    .code-block {
      max-width: 100%;
      overflow-x: auto;
    }
    
    .code-content pre {
      font-size: 0.8rem;
    }
  }
</style>
