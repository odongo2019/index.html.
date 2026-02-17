<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Personal portfolio showcasing front-end development skills and projects.">
  <title>Kevin Odongo | Front-End Developer</title>
  <link rel="stylesheet" href="styles.css">
</head>

<body>
  <header>
    <nav role="navigation" aria-label="Main navigation">
      <ul>
        <li><a href="#about-me">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#skills">Skills</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
    <h1>Kevin Odongo</h1>
    <p>Front-End Developer</p>
  </header>

  <main>
    <section id="about-me">
      <h2>About Me</h2>
      <p>
        I am a front-end developer passionate about building accessible,
        user-friendly web applications using modern technologies.
      </p>
    </section>

    <section id="projects">
      <h2>Projects</h2>

      <article>
        <figure>
          <img src="project1.png" alt="Screenshot of Portfolio Website Project">
          <figcaption>Personal Portfolio Website</figcaption>
        </figure>
        <p>A responsive portfolio website built using semantic HTML and CSS.</p>
      </article>

      <article>
        <figure>
          <img src="project2.png" alt="Screenshot of Task Management App">
          <figcaption>Task Management App</figcaption>
        </figure>
        <p>A simple task manager demonstrating front-end structure and layout.</p>
      </article>
    </section>

    <section id="skills">
      <h2>Skills</h2>
      <ul>
        <li>HTML5</li>
        <li>CSS3</li>
        <li>JavaScript</li>
        <li>Accessibility (WCAG)</li>
        <li>SEO Fundamentals</li>
      </ul>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <form>
        <label for="name">Name</label>
        <input id="name" type="text" name="name" required>

        <label for="email">Email</label>
        <input id="email" type="email" name="email" required>

        <label for="message">Message</label>
        <textarea id="message" name="message" rows="4" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2026 Kevin Odongo. All rights reserved.</p>
  </footer>
</body>
</html>
