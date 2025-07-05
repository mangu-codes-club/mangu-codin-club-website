<script>
  const clubEmail = "mangucodingclub@proton.me";
  const phone = "+1234567890";
</script>

<style>
  .sponsor-page {
    max-width: 600px;
    margin: 2rem auto;
    padding: 2rem;
    border-radius: 1rem;
    background: #f7fafd;
    box-shadow: 0 2px 8px rgba(0,0,0,0.07);
    text-align: center;
  }
  .sponsor-page h1 {
    font-size: 2.3rem;
    margin-bottom: 1rem;
    color: #0077cc;
  }
  .sponsor-page p {
    font-size: 1.2rem;
    margin-bottom: 1.5rem;
    color: #333;
  }
  .sponsor-benefits {
    text-align: left;
    margin: 1.5rem 0;
  }
  .sponsor-benefits li {
    margin-bottom: 0.7rem;
  }
  .contact-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-top: 2rem;
  }
  .contact-buttons button {
    padding: 0.7rem 1.5rem;
    font-size: 1rem;
    border: none;
    border-radius: 0.5rem;
    background: #0077cc;
    color: #fff;
    cursor: pointer;
    transition: background 0.2s;
  }
  .contact-buttons button:hover {
    background: #005fa3;
  }
</style>

<div class="sponsor-page" id = 'sponsor-page'>
  <h1>Sponsor Us</h1>
  <p>
    Support our club’s mission to empower students through coding!<br>
    Your sponsorship helps us organize functions, hackathons, and impactful projects.
  </p>
  <ul class="sponsor-benefits">
    <li>Enable student-led hackathons and workshops</li>
    <li>Support club functions and outreach</li>
    <li>Help us acquire resources and tools</li>
    <li>Get recognized as a valued partner in our community</li>
  </ul>
  <p>
    Interested in sponsoring or partnering with us? Reach out below!
  </p>
  <div class="contact-buttons">
    <a href="mailto:{clubEmail}">
      <button type="button">Email Club</button>
    </a>
    <a href="tel:{phone}">
      <button type="button">Call Club</button>
    </a>
  </div>
</div>