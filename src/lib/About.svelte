<section id="about" class="about">
  <div class="container">
    <div class="section-header">
      <h2>About Mangu Coding Club</h2>
      <p>Empowering the next generation of developers</p>
    </div>
    
    <div class="about-content">
      <div class="about-text">
        <h3>Our Mission</h3>
        <p>
          At Mangu Coding Club, we believe that coding is not just about writing code—it's about 
          solving problems, building communities, and creating innovative solutions that make a 
          difference. We're dedicated to fostering a supportive environment where beginners can 
          learn, experienced developers can share knowledge, and everyone can grow together.
        </p>
        
        <h3>What We Do</h3>
        <ul>
          <li>🚀 <strong>Workshops & Tutorials:</strong> Regular sessions on various programming languages and technologies</li>
          <li>🏗️ <strong>Project Building:</strong> Collaborative projects to build real-world applications</li>
          <li>🎯 <strong>Hackathons:</strong> Exciting coding competitions and innovation challenges</li>
          <li>🤝 <strong>Networking:</strong> Connect with like-minded developers and industry professionals</li>
          <li>📚 <strong>Mentorship:</strong> Pair experienced members with newcomers for guidance</li>
        </ul>
      </div>
      
      <div class="stats">
        <div class="stat-card">
<<<<<<< HEAD
          <div class="stat-number">50+</div>
=======
          <div class="stat-number">150+</div>
>>>>>>> b9bf38f55b41b959d590260d596e3e661d555633
          <div class="stat-label">Active Members</div>
        </div>
        
        <div class="stat-card">
          <div class="stat-number">50+</div>
          <div class="stat-label">Projects Built</div>
        </div>
        
        <div class="stat-card">
          <div class="stat-number">25+</div>
          <div class="stat-label">Workshops Held</div>
        </div>
        
        <div class="stat-card">
          <div class="stat-number">12+</div>
          <div class="stat-label">Languages Covered</div>
        </div>
      </div>
    </div>
    
    <div class="technologies">
      <h3>Technologies We Work With</h3>
      <div class="tech-grid">
        <div class="tech-item">JavaScript</div>
        <div class="tech-item">Python</div>
        <div class="tech-item">Java</div>
        <div class="tech-item">React</div>
        <div class="tech-item">Node.js</div>
        <div class="tech-item">Svelte</div>
        <div class="tech-item">MongoDB</div>
        <div class="tech-item">PostgreSQL</div>
        <div class="tech-item">Docker</div>
        <div class="tech-item">AWS</div>
        <div class="tech-item">Git</div>
        <div class="tech-item">TypeScript</div>
      </div>
    </div>
  </div>
</section>

<style>
  .about {
    padding: 6rem 0;
    background: #f8f9fa;
  }
  
  .container {
    max-width: 1200px;
    margin: 0 auto;
    padding: 0 2rem;
  }
  
  .section-header {
    text-align: center;
    margin-bottom: 4rem;
  }
  
  .section-header h2 {
    font-size: 2.5rem;
    font-weight: bold;
    color: #333;
    margin: 0 0 1rem 0;
  }
  
  .section-header p {
    font-size: 1.2rem;
    color: #666;
    margin: 0;
  }
  
  .about-content {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 4rem;
    margin-bottom: 4rem;
  }
  
  .about-text h3 {
    font-size: 1.5rem;
    color: #333;
    margin: 0 0 1rem 0;
  }
  
  .about-text p {
    font-size: 1.1rem;
    line-height: 1.7;
    color: #555;
    margin-bottom: 2rem;
  }
  
  .about-text ul {
    list-style: none;
    padding: 0;
    margin: 0;
  }
  
  .about-text li {
    font-size: 1.1rem;
    line-height: 1.7;
    color: #555;
    margin-bottom: 1rem;
    padding-left: 0;
  }
  
  .stats {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 1.5rem;
  }
  
  .stat-card {
    background: white;
    padding: 2rem;
    border-radius: 12px;
    text-align: center;
    box-shadow: 0 4px 20px rgba(0,0,0,0.1);
  }
  
  .stat-number {
    font-size: 2.5rem;
    font-weight: bold;
    color: #667eea;
    margin-bottom: 0.5rem;
  }
  
  .stat-label {
    font-size: 1rem;
    color: #666;
    font-weight: 500;
  }
  
  .technologies {
    text-align: center;
  }
  
  .technologies h3 {
    font-size: 1.8rem;
    color: #333;
    margin: 0 0 2rem 0;
  }
  
  .tech-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(120px, 1fr));
    gap: 1rem;
  }
  
  .tech-item {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 1rem;
    border-radius: 8px;
    font-weight: 600;
    text-align: center;
    transition: transform 0.3s ease;
  }
  
  .tech-item:hover {
    transform: translateY(-4px);
  }
  
  @media (max-width: 768px) {
    .about {
      padding: 4rem 0;
    }
    
    .section-header h2 {
      font-size: 2rem;
    }
    
    .about-content {
      grid-template-columns: 1fr;
      gap: 3rem;
    }
    
    .stats {
      grid-template-columns: 1fr;
      gap: 1rem;
    }
    
    .stat-card {
      padding: 1.5rem;
    }
    
    .stat-number {
      font-size: 2rem;
    }
    
    .tech-grid {
      grid-template-columns: repeat(auto-fit, minmax(100px, 1fr));
      gap: 0.8rem;
    }
    
    .tech-item {
      padding: 0.8rem;
      font-size: 0.9rem;
    }
  }
</style>
