<template>
  <div class="main-container">
    <nav class="navbar">
      <ul>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#technologies">Technologies</a></li>
      </ul>
    </nav>

    <header class="header">
      <h1>Amer Sawan</h1>
      <h2>Software Developer</h2>
    </header>

    <section id="about" class="about-section">
      <h2>About Me</h2>
      <p>
        I am a recently graduated software engineer with a focus on website and
        web development, primarily in backend technologies. Proficient in
        JavaScript and Python, I bring valuable programming skills to the table.
        Fluent in four languages—Arabic, French, and Spanish—I possess a
        multilingual advantage that allows me to communicate effectively across
        diverse audiences. With a strong aptitude for both communication and
        presentation, I am ready to tackle new challenges and contribute
        meaningfully to any team or project.
      </p>
    </section>

    <section id="projects" class="projects-section">
      <h2>Projects</h2>
      <div class="project">
        <h3>Pre-Graduation Project</h3>
        <p>
          I developed the backend for a student platform using PHP and MySQL.
          This platform enabled students to communicate, share study files,
          calculate GPA, chat, and make posts with comments. Additionally, it
          featured a chatbot for answering student questions. My work focused on
          ensuring robust functionality and smooth data management.
        </p>
        <a href="https://github.com/yourprofile/projectname">View on GitHub</a>
        <h3>Graduation Project</h3>
        <p>
          I developed the backend of a real estate app using Laravel, MySQL, and
          Postman for managing buying, selling, and renting properties. My role
          involved creating secure user authentication, managing property
          listings, and handling transactions efficiently. This project enhanced
          my skills in backend development and API integration, ensuring a
          robust and scalable system.
        </p>
        <a href="https://github.com/yourprofile/projectname">View on GitHub</a>
        <h3>Printly</h3>
        <p>
          I developed a print-on-demand website, handling both frontend and
          backend using PHP, HTML, CSS, and MySQL. The site allowed users to
          customize and request prints on clothing or objects. My work ensured a
          well-compartmentalized structure, providing a seamless user experience
          and efficient order processing. This project honed my full-stack
          development skills and user interface design.
        </p>
        <a href="https://github.com/yourprofile/projectname">View on GitHub</a>
        <h3>e-tech marketing website</h3>
        <p>
          I designed and developed both the frontend and backend of a smartphone
          e-commerce website using HTML, CSS, PHP, and MySQL. The platform
          enabled users to search for and purchase smartphones, providing a
          seamless shopping experience. My work ensured a responsive design,
          efficient product search, and secure transaction processing.
        </p>
        <a href="https://github.com/yourprofile/projectname">View on GitHub</a>
      </div>
    </section>

    <section id="technologies" class="technologies-section">
      <h2>Technologies Studied</h2>
      <div class="technology-grid">
        <div class="technology-item">
          <h3>HTML</h3>
        </div>
        <div class="technology-item">
          <h3>CSS</h3>
        </div>
        <div class="technology-item">
          <h3>PHP</h3>
        </div>
        <div class="technology-item">
          <h3>Laravel</h3>
        </div>
        <div class="technology-item">
          <h3>JS</h3>
        </div>
        <div class="technology-item">
          <h3>C++</h3>
        </div>
        <div class="technology-item">
          <h3>SQL</h3>
        </div>
      </div>
    </section>

    <footer class="footer">
      <div class="social-links">
        <a href="https://github.com/bojackA/">
          <span>Github</span>
        </a>
        <a
          href="https://www.linkedin.com/in/amer-sawan-a025581ab?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app"
        >
          <span>LinkedIn</span>
        </a>
        <a href="https://x.com/amerthinks?s=35">
          <span>Twitter</span>
        </a>
        <a
          href="https://www.instagram.com/amer_sawan?igsh=MWw4ajBxcWV4ZHpkOQ=="
        >
          <span>Instagram</span>
        </a>
      </div>
    </footer>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
body {
  margin: 0;
  padding: 0;
  font-family: Arial, sans-serif;
  background-color: #f7f7f7;
  color: #333;
}

.main-container {
  display: flex;
  flex-direction: column;
  align-items: center;
  background-color: #fff;
}

.navbar {
  width: 100%;
  background-color: #333;
  padding: 1rem;
  margin-top: 0; /* Ensure no margin is applied */
  position: fixed; /* Fixes the navbar at the top of the screen */
  top: 0;
  left: 0;
  z-index: 1000; /* Ensures the navbar is on top of other content */
}

.navbar ul {
  display: flex;
  justify-content: center;
  list-style: none;
  padding: 0;
  margin: 0; /* Remove default margins */
}

.navbar ul li {
  margin: 0 1rem;
}

.navbar ul li a {
  color: #fff;
  text-decoration: none;
  font-size: 1.2rem;
}

.header {
  text-align: center;
  padding: 2rem;
  background-color: #3498db;
  color: #fff;
  width: 100%;
  margin-top: 2rem; /* Adjusted margin-top */
}

.about-section,
.projects-section,
.technologies-section,
.contact-section {
  padding: 2rem;
  width: 80%;
  max-width: 800px;
  margin: 2rem 0;
  background-color: #f1f1f1;
  border-radius: 10px;
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
}

.project {
  margin-bottom: 1rem;
}

.technologies-section .technology-grid {
  display: grid;
  grid-template-columns: repeat(auto-fill, minmax(100px, 1fr));
  gap: 1rem;
}

.technologies-section .technology-item {
  background-color: #3498db;
  color: #fff;
  text-align: center;
  padding: 1rem;
  border-radius: 5px;
}

.contact-section form {
  display: flex;
  flex-direction: column;
}

.contact-section form input,
.contact-section form textarea {
  margin-bottom: 1rem;
  padding: 1rem;
  border: 1px solid #ccc;
  border-radius: 5px;
}

.contact-section form button {
  padding: 1rem;
  background-color: #3498db;
  color: #fff;
  border: none;
  border-radius: 5px;
  cursor: pointer;
}

.footer {
  width: 100%;
  padding: 1rem;
  background-color: #333;
  color: #fff;
  display: flex;
  justify-content: center;
  position: fixed;
  bottom: 0; /* Fix the footer to the bottom of the viewport */
}
.footer .social-links {
  display: flex;
  justify-content: space-around;
  width: 50%;
}

.footer .social-links a {
  display: flex;
  align-items: center;
  color: #fff;
  text-decoration: none;
}

.footer .social-links img {
  margin-right: 0.5rem;
}
</style>
