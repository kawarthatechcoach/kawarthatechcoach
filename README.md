<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Kawartha Tech Coach</title>
<style>
  /* Reset */
  * {
    margin: 0; padding: 0; box-sizing: border-box;
  }

  body {
    font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
    line-height: 1.6;
    background: #f9fcfc;
    color: #2a3a3a;
  }

  header {
    background-color: #2a7f62; /* deep green */
    color: white;
    padding: 1rem 2rem;
    text-align: center;
  }

  header h1 {
    font-size: 2.2rem;
  }

  nav {
    background: #38a27d; /* lighter green */
    display: flex;
    justify-content: center;
    gap: 2rem;
    padding: 1rem 0;
  }

  nav a {
    color: white;
    text-decoration: none;
    font-weight: 600;
    font-size: 1.1rem;
  }

  nav a:hover,
  nav a:focus {
    text-decoration: underline;
  }

  main {
    max-width: 900px;
    margin: 2rem auto;
    padding: 0 1rem;
  }

  section {
    margin-bottom: 3rem;
  }

  h2 {
    color: #2a7f62;
    margin-bottom: 1rem;
  }

  p {
    margin-bottom: 1rem;
  }

  .btn-primary {
    display: inline-block;
    background-color: #2a7f62;
    color: white;
    padding: 0.6rem 1.2rem;
    border-radius: 5px;
    text-decoration: none;
    font-weight: 700;
    transition: background-color 0.3s ease;
  }

  .btn-primary:hover,
  .btn-primary:focus {
    background-color: #1e5a45;
  }

  /* Testimonials styling */
  .testimonial {
    background-color: #e0f0ea;
    border-left: 5px solid #2a7f62;
    padding: 1rem 1.5rem;
    margin-bottom: 1rem;
    font-style: italic;
  }

  /* Contact form */
  form {
    display: flex;
    flex-direction: column;
    gap: 1rem;
    max-width: 400px;
  }

  label {
    font-weight: 600;
  }

  input, textarea {
    padding: 0.5rem;
    border: 1px solid #ccc;
    border-radius: 4px;
    font-family: inherit;
    font-size: 1rem;
  }

  textarea {
    resize: vertical;
    min-height: 100px;
  }

  input[type="submit"] {
    background-color: #2a7f62;
    color: white;
    border: none;
    cursor: pointer;
    font-weight: 700;
    transition: background-color 0.3s ease;
  }

  input[type="submit"]:hover,
  input[type="submit"]:focus {
    background-color: #1e5a45;
  }

  footer {
    background-color: #2a7f62;
    color: white;
    text-align: center;
    padding: 1rem;
    font-size: 0.9rem;
  }

  /* Responsive */
  @media (max-width: 600px) {
    nav {
      flex-direction: column;
      gap: 1rem;
    }

    main {
      margin: 1rem;
      padding: 0 0.5rem;
    }
  }
</style>
</head>
<body>

<header>
  <h1>Kawartha Tech Coach</h1>
  <p>Your friendly guide to mastering technology</p>
</header>

<nav aria-label="Primary navigation">
  <a href="#home" tabindex="0">Home</a>
  <a href="#about" tabindex="0">About</a>
  <a href="#services" tabindex="0">Services</a>
  <a href="#testimonials" tabindex="0">Testimonials</a>
  <a href="#contact" tabindex="0">Contact</a>
</nav>

<main>
  <section id="home" tabindex="0">
    <h2>Welcome to Kawartha Tech Coach</h2>
    <p>We specialize in helping seniors and their families gain confidence and independence with technology. Whether it's your smartphone, tablet, laptop, or smart TV, we make learning simple, enjoyable, and stress-free.</p>
    <a href="#contact" class="btn-primary">Book a Free Consultation</a>
  </section>

  <section id="about" tabindex="0">
    <h2>About Us</h2>
    <p>Kawartha Tech Coach was founded with a passion for empowering seniors to stay connected in today's digital world. We believe technology should be accessible and friendly to everyone, regardless of experience.</p>
    <p>Our approach is patient, personalized, and hands-on — meeting you where you are and building skills at your pace.</p>
  </section>

  <section id="services" tabindex="0">
    <h2>Services</h2>
    <ul>
      <li><strong>One-on-One Coaching:</strong> Personalized tech lessons tailored to your needs.</li>
      <li><strong>Group Workshops:</strong> Fun, interactive sessions on popular devices and apps.</li>
      <li><strong>Consulting:</strong> Help choosing the right devices and software for your lifestyle.</li>
      <li><strong>Remote Support:</strong> Assistance via phone or video call when in-person isn't possible.</li>
    </ul>
  </section>

  <section id="testimonials" tabindex="0">
    <h2>What Our Clients Say</h2>
    <div class="testimonial">"Thanks to Kawartha Tech Coach, I finally understand how to use my tablet to video chat with my grandchildren. Highly recommend!" – Mary S.</div>
    <div class="testimonial">"Patient, knowledgeable, and friendly. The workshops were enjoyable and helpful." – John D.</div>
    <div class="testimonial">"I never thought I could learn so much about my smartphone. Now I feel connected and independent." – Alice M.</div>
  </section>

  <section id="contact" tabindex="0">
    <h2>Contact Us</h2>
    <p>Have questions or want to book your free consultation? Reach out anytime!</p>
    <form action="mailto:youremail@example.com" method="post" enctype="text/plain" aria-label="Contact form">
      <label for="name">Name:</label>
      <input type="text" id="name" name="Name" required />

      <label for="email">Email:</label>
      <input type="email" id="email" name="Email" required />

      <label for="message">Message:</label>
      <textarea id="message" name="Message" required></textarea>

      <input type="submit" value="Send" />
    </form>
  </section>
</main>

<footer>
  <p>&copy; 2025 Kawartha Tech Coach. All rights reserved.</p>
</footer>

</body>
</html>
