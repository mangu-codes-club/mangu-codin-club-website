<script lang="ts">
  const upcomingEvents = [
    {
<<<<<<< HEAD
      title: "Tech Gala",
      date: "July 19, 2025",
      time: "9:00 AM - 4:00 PM",
      location: "Mangu High School ",
      description: "Show case of innovative projects by students , networking , learning and fun.",
      type: "Exhibition"
    },
 
=======
      title: "JavaScript Fundamentals Workshop",
      date: "July 15, 2024",
      time: "6:00 PM - 8:00 PM",
      location: "Main Conference Room",
      description: "Learn the basics of JavaScript programming, from variables to functions.",
      type: "Workshop"
    },
    {
      title: "React Bootcamp",
      date: "July 22, 2024",
      time: "10:00 AM - 4:00 PM",
      location: "Tech Lab",
      description: "Build your first React application with hands-on exercises.",
      type: "Bootcamp"
    },
    {
      title: "Monthly Hackathon",
      date: "July 29, 2024",
      time: "9:00 AM - 9:00 PM",
      location: "Innovation Hub",
      description: "24-hour coding challenge with prizes for the best projects.",
      type: "Hackathon"
    }
>>>>>>> b9bf38f55b41b959d590260d596e3e661d555633
  ];

  const pastEvents = [
    {
<<<<<<< HEAD
      title: "Web Development for Beginners",
      date: "March 20, 2025",
      attendees: 45,
      description: "Introduction to Python programming language."
    },
 
=======
      title: "Python for Beginners",
      date: "June 20, 2024",
      attendees: 45,
      description: "Introduction to Python programming language."
    },
    {
      title: "Git & GitHub Workshop",
      date: "June 15, 2024",
      attendees: 38,
      description: "Version control essentials for developers."
    },
    {
      title: "Web Development Bootcamp",
      date: "June 10, 2024",
      attendees: 52,
      description: "Full-stack web development fundamentals."
    }
>>>>>>> b9bf38f55b41b959d590260d596e3e661d555633
  ];
</script>

<section id="events" class="events">
  <div class="container">
    <div class="section-header">
      <h2>Events & Activities</h2>
      <p>Join us for exciting learning opportunities and community building</p>
    </div>

    <div class="events-content">
      <div class="upcoming-events">
        <h3>🗓️ Upcoming Events</h3>
        <div class="events-grid">
          {#each upcomingEvents as event}
            <div class="event-card upcoming">
              <div class="event-type">{event.type}</div>
              <h4>{event.title}</h4>
              <div class="event-details">
                <div class="event-detail">
                  <span class="icon">📅</span>
                  <span>{event.date}</span>
                </div>
                <div class="event-detail">
                  <span class="icon">⏰</span>
                  <span>{event.time}</span>
                </div>
                <div class="event-detail">
                  <span class="icon">📍</span>
                  <span>{event.location}</span>
                </div>
              </div>
              <p class="event-description">{event.description}</p>
<<<<<<< HEAD
            <a
              class="register-btn"
              href="mailto:mangucodingclub@proton.me?subject=Event Registration&body=I would like to register for the {event.title}."
              target="_blank"
            >
              Register Now
            </a>
=======
              <button class="register-btn">Register Now</button>
>>>>>>> b9bf38f55b41b959d590260d596e3e661d555633
            </div>
          {/each}
        </div>
      </div>

      <div class="past-events">
        <h3>📚 Recent Activities</h3>
        <div class="past-events-list">
          {#each pastEvents as event}
            <div class="past-event-item">
              <div class="past-event-info">
                <h4>{event.title}</h4>
                <p class="past-event-date">{event.date}</p>
                <p class="past-event-description">{event.description}</p>
              </div>
              <div class="past-event-stats">
                <div class="attendees">
                  <span class="attendees-count">{event.attendees}</span>
                  <span class="attendees-label">Attendees</span>
                </div>
              </div>
            </div>
          {/each}
        </div>
      </div>
    </div>

    <div class="cta-section">
      <h3>Want to stay updated?</h3>
      <p>Join our community to get notified about upcoming events and activities!</p>
      <div class="cta-buttons">
        <button class="btn primary">Join Discord</button>
        <button class="btn secondary">Subscribe Newsletter</button>
      </div>
    </div>
  </div>
</section>

<style>
  .events {
    padding: 6rem 0;
    background: white;
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
  
  .events-content {
    display: grid;
    grid-template-columns: 2fr 1fr;
    gap: 4rem;
    margin-bottom: 4rem;
  }
  
  .upcoming-events h3,
  .past-events h3 {
    font-size: 1.8rem;
    color: #333;
    margin: 0 0 2rem 0;
  }
  
  .events-grid {
    display: grid;
    gap: 2rem;
  }
  
  .event-card {
    background: #f8f9fa;
    border-radius: 12px;
    padding: 2rem;
    border-left: 4px solid #667eea;
    transition: transform 0.3s ease, box-shadow 0.3s ease;
  }
  
  .event-card:hover {
    transform: translateY(-4px);
    box-shadow: 0 8px 30px rgba(0,0,0,0.12);
  }
  
  .event-type {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 0.5rem 1rem;
    border-radius: 15px;
    font-size: 0.8rem;
    font-weight: 600;
    display: inline-block;
    margin-bottom: 1rem;
  }
  
  .event-card h4 {
    font-size: 1.3rem;
    color: #333;
    margin: 0 0 1rem 0;
  }
  
  .event-details {
    margin-bottom: 1rem;
  }
  
  .event-detail {
    display: flex;
    align-items: center;
    gap: 0.5rem;
    margin-bottom: 0.5rem;
    color: #666;
    font-size: 0.9rem;
  }
  
  .icon {
    font-size: 1rem;
  }
  
  .event-description {
    color: #555;
    line-height: 1.6;
    margin-bottom: 1.5rem;
  }
  
  .register-btn {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    border: none;
    padding: 0.8rem 1.5rem;
    border-radius: 8px;
    font-weight: 600;
    cursor: pointer;
    transition: transform 0.3s ease;
  }
  
  .register-btn:hover {
    transform: translateY(-2px);
  }
  
  .past-events-list {
    display: grid;
    gap: 1.5rem;
  }
  
  .past-event-item {
    background: #f8f9fa;
    border-radius: 8px;
    padding: 1.5rem;
    display: flex;
    justify-content: space-between;
    align-items: flex-start;
    gap: 1rem;
  }
  
  .past-event-info h4 {
    font-size: 1.1rem;
    color: #333;
    margin: 0 0 0.5rem 0;
  }
  
  .past-event-date {
    font-size: 0.9rem;
    color: #667eea;
    font-weight: 600;
    margin: 0 0 0.5rem 0;
  }
  
  .past-event-description {
    font-size: 0.9rem;
    color: #666;
    margin: 0;
  }
  
  .past-event-stats {
    text-align: center;
  }
  
  .attendees-count {
    display: block;
    font-size: 1.5rem;
    font-weight: bold;
    color: #667eea;
  }
  
  .attendees-label {
    font-size: 0.8rem;
    color: #666;
  }
  
  .cta-section {
    background: linear-gradient(135deg, #667eea 0%, #764ba2 100%);
    color: white;
    padding: 3rem;
    border-radius: 12px;
    text-align: center;
  }
  
  .cta-section h3 {
    font-size: 1.8rem;
    margin: 0 0 1rem 0;
  }
  
  .cta-section p {
    font-size: 1.1rem;
    margin: 0 0 2rem 0;
    opacity: 0.9;
  }
  
  .cta-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
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
  
  @media (max-width: 768px) {
    .events {
      padding: 4rem 0;
    }
    
    .section-header h2 {
      font-size: 2rem;
    }
    
    .events-content {
      grid-template-columns: 1fr;
      gap: 3rem;
    }
    
    .event-card {
      padding: 1.5rem;
    }
    
    .past-event-item {
      flex-direction: column;
      gap: 1rem;
    }
    
    .cta-section {
      padding: 2rem;
    }
    
    .cta-buttons {
      flex-direction: column;
      align-items: center;
    }
    
    .btn {
      width: 100%;
      max-width: 250px;
    }
  }
</style>
