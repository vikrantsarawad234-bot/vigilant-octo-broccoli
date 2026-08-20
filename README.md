# vigilant-octo-broccoli
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Portfolio of Jane Doe - Full-stack web developer and accessibility specialist.">
  <meta name="author" content="Jane Doe">
  
  <!-- Open Graph Meta Tags for SEO -->
  <meta property="og:title" content="Jane Doe | Developer Portfolio">
  <meta property="og:description" content="Explore projects, technical skills, and contact details for Jane Doe.">
  <meta property="og:type" content="website">
  
  <title>Jane Doe | Web Developer Portfolio</title>
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <!-- Keyboard Navigation Accessibility Link -->
  <a href="#main-content" class="skip-link">Skip to main content</a>

  <header>
    <nav aria-label="Main Navigation">
      <ul>
        <li><a href="#about" aria-current="page">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <main id="main-content">
    <section id="about" aria-labelledby="about-heading">
      <h1 id="about-heading">Jane Doe</h1>
      <p>Full-Stack Engineer focusing on performant, accessible web software.</p>
    </section>

    <section id="projects" aria-labelledby="projects-heading">
      <h2 id="projects-heading">Featured Work</h2>
      <article>
        <h3>Accessible E-Commerce Dashboard</h3>
        <p>Built with semantic HTML5 and React to pass WCAG 2.1 AA compliance.</p>
        <a href="https://github.com/example/repo" aria-label="View source code for Accessible E-Commerce Dashboard on GitHub">View Code</a>
      </article>
    </section>

    <section id="contact" aria-labelledby="contact-heading">
      <h2 id="contact-heading">Contact Me</h2>
      <form action="#" method="POST" aria-describedby="form-instructions">
        <p id="form-instructions">All fields are required.</p>

        <div class="form-field">
          <label for="user-name">Full Name</label>
          <input type="text" id="user-name" name="name" autocomplete="name" required aria-required="true">
        </div>

        <div class="form-field">
          <label for="user-email">Email Address</label>
          <input type="email" id="user-email" name="email" autocomplete="email" required aria-required="true">
        </div>

        <div class="form-field">
          <label for="user-message">Message</label>
          <textarea id="user-message" name="message" rows="5" required aria-required="true"></textarea>
        </div>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Jane Doe. Built with semantic HTML5.</p>
  </footer>
</body>
</html>
