<script>
  let chair = {
    name: "Ken Karoki",
    role: "Chairperson",
    image: "https://avatars.githubusercontent.com/u/35598221?v=4"
  };

  let patron = {
    name: "Mr. Waswa",
    role: "Patron",
    image: "https://avatars.githubusercontent.com/u/35598221?v=4",
    contacts: {
      phone: "+1234567890",
      email: "waswa@example.com",
      clubEmail: "mangucodingclub@proton.me"
    }
  };
</script>

<style>
  .mentor-page {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 2rem;
  }

  .mentor-page h1 {
    font-size: 2.5rem;
    margin-bottom: 1.5rem;
  }

  .mentor-page .mentor-info {
    display: flex;
    flex-direction: column;
    align-items: center;
    margin-bottom: 2rem;
  }

  .mentor-page img {
    width: 150px;
    height: 150px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 1rem;
  }

  .mentor-page p {
    text-align: center;
    margin-bottom: 1rem;
  }

  .mentor-page .mentor-info:not(:last-child) {
    margin-bottom: 3rem;
  }

  .mentor-page .mentor-info p {
    font-size: 1.2rem;
  }

  .mentor-page .mentor-info h3 {
    font-size: 1.5rem;
    margin-bottom: 1rem;
  }

  .mentor-page .mentor-info .mentor-role {
    font-size: 1.2rem;
    color: #666;
  }

  .contact-buttons {
    display: flex;
    gap: 1rem;
    justify-content: center;
    margin-top: 1.5rem;
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

<div class="mentor-page" id = 'mentor-page'>
  <h1>Be a Mentor</h1>
  <div class="mentor-info">
    <img src={patron.image} alt={patron.name} />
    <h3>{patron.name}</h3>
    <p class="mentor-role">{patron.role}</p>
  </div>
  <div class="mentor-info">
    <img src={chair.image} alt={chair.name} />
    <h3>{chair.name}</h3>
    <p class="mentor-role">{chair.role}</p>
  </div>
  <p>
    As a mentor, you will be expected to guide and support students in their coding journey. You will also be expected to commit to attending club meetings and events regularly. If you are interested in being a mentor, please contact the club chairperson at <a href="mailto:kenkaroki92@gmail.com">Chairmans Email</a>.
    <a href="mailto:kenkaroki92@gmail.com">Patrons Email</a>.
  </p>
  <div class="contact-buttons">
    <a href="mailto:{patron.contacts.clubEmail}">
      <button type="button">Email Club</button>
    </a>
    <a href="mailto:{patron.contacts.email}">
      <button type="button">Email Patron</button>
    </a>
    <a href="tel:{patron.contacts.phone}">
      <button type="button">Call Patron</button>
    </a>
  </div>
</div>
