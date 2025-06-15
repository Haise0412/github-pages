<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Harish Kumar S - Portfolio</title>
  <style>
    /* Root variables and font setup */
    @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@400;600;700&display=swap');

    :root {
      --bg-color: #ffffff;
      --text-color: #6b7280;
      --heading-color: #111827;
      --card-bg: #f9fafb;
      --card-shadow: rgba(0,0,0,0.05);
      --radius: 0.75rem;
      --max-width: 1200px;
      --transition: 0.3s ease;
      --primary-color: #111827;
      --button-bg: #111827;
      --button-hover-bg: #374151;
    }

    /* Reset and base */
    * {
      box-sizing: border-box;
    }

    body {
      margin: 0;
      font-family: 'Poppins', sans-serif;
      background-color: var(--bg-color);
      color: var(--text-color);
      line-height: 1.6;
      font-size: 16px;
    }

    a {
      color: var(--primary-color);
      text-decoration: none;
      transition: color var(--transition);
    }

    a:hover, a:focus {
      color: var(--button-hover-bg);
      outline: none;
    }

    /* Container */
    .container {
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 0 1rem;
    }

    /* Header */
    header {
      position: sticky;
      top: 0;
      background: var(--bg-color);
      border-bottom: 1px solid #e5e7eb;
      z-index: 1000;
    }

    nav {
      display: flex;
      justify-content: space-between;
      align-items: center;
      max-width: var(--max-width);
      margin: 0 auto;
      padding: 1rem;
    }

    .logo {
      font-weight: 700;
      font-size: 1.5rem;
      color: var(--primary-color);
    }

    .nav-links {
      display: flex;
      gap: 2rem;
      font-weight: 600;
      font-size: 0.95rem;
    }

    .nav-links a {
      padding: 0.5rem;
      border-radius: 4px;
      transition: background-color var(--transition), color var(--transition);
    }

    .nav-links a:hover {
      background-color: var(--card-bg);
    }

    /* Hero Section */
    .hero {
      padding: 6rem 1rem 4rem;
      text-align: center;
      background: #f3f4f6;
      color: var(--heading-color);
      border-radius: var(--radius);
      margin: 3rem auto 5rem;
      max-width: 720px;
      box-shadow: 0 4px 12px var(--card-shadow);
    }

    .hero h1 {
      font-size: 3rem;
      font-weight: 800;
      margin-bottom: 1rem;
      line-height: 1.1;
    }

    .hero p {
      font-size: 1.25rem;
      margin-bottom: 2rem;
      color: var(--text-color);
    }

    .btn-primary {
      display: inline-block;
      background-color: var(--button-bg);
      color: #fff;
      padding: 0.75rem 2rem;
      border-radius: 0.5rem;
      font-weight: 700;
      font-size: 1.1rem;
      cursor: pointer;
      border: none;
      transition: background-color var(--transition);
      text-decoration: none;
      user-select: none;
    }

    .btn-primary:hover,
    .btn-primary:focus {
      background-color: var(--button-hover-bg);
      outline: none;
    }

    /* Sections */
    section {
      padding-top: 4rem;
      padding-bottom: 5rem;
    }

    section > h2 {
      font-size: 2rem;
      font-weight: 700;
      color: var(--heading-color);
      margin-bottom: 2rem;
      text-align: center;
    }

    /* Cards Grid */
    .grid-3 {
      display: grid;
      grid-template-columns: repeat(auto-fit,minmax(280px,1fr));
      gap: 2rem;
    }

    /* Card */
    .card {
      background: var(--card-bg);
      padding: 1.75rem 2rem;
      border-radius: var(--radius);
      box-shadow: 0 2px 6px var(--card-shadow);
      display: flex;
      flex-direction: column;
      justify-content: space-between;
      transition: transform 0.3s ease, box-shadow 0.3s ease;
    }

    .card:hover {
      transform: translateY(-5px);
      box-shadow: 0 10px 25px rgba(0,0,0,0.12);
    }

    .card h3 {
      font-size: 1.25rem;
      font-weight: 700;
      margin-bottom: 0.75rem;
      color: var(--primary-color);
    }

    .card p {
      flex-grow: 1;
      font-size: 1rem;
      color: var(--text-color);
      margin: 0.3rem 0 1rem;
      white-space: pre-line;
    }

    /* Lists */
    ul.skills-list,
    ul.cert-list {
      list-style: none;
      padding-left: 0;
      margin: 0;
    }

    ul.skills-list li,
    ul.cert-list li {
      margin-bottom: 0.5rem;
      color: var(--text-color);
      font-weight: 500;
    }

    /* Contact Section */
    .contact-info {
      text-align: center;
      font-size: 1rem;
      color: var(--text-color);
      line-height: 1.5;
      max-width: 480px;
      margin: 0 auto;
    }

    .contact-info a {
      color: var(--primary-color);
      font-weight: 600;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 2rem 1rem;
      font-size: 0.9rem;
      color: #9ca3af;
      border-top: 1px solid #e5e7eb;
    }

    /* Responsive tweaks */
    @media (max-width: 600px) {
      .hero h1 {
        font-size: 2.25rem;
      }

      .hero p {
        font-size: 1rem;
      }
    }
  </style>
</head>
<body>
  <header>
    <nav class="container" aria-label="Primary Navigation">
      <a href="#hero" class="logo">Harish Kumar S</a>
      <div class="nav-links" role="navigation" aria-label="Main menu">
        <a href="#about">About</a>
        <a href="#education">Education</a>
        <a href="#skills">Skills</a>
        <a href="#certificates">Certificates</a>
        <a href="#experience">Experience</a>
        <a href="#contact">Contact</a>
      </div>
    </nav>
  </header>

  <main class="container" id="hero">
    <section class="hero" aria-label="Introduction">
      <h1>Cybersecurity & Full Stack Developer Portfolio</h1>
      <p>Enthusiast in Cyber Forensics, Secure Development, and Real-World Projects. Exploring modern tech and building solutions.</p>
      <a href="https://linkedin.com/in/s-harishkumar" target="_blank" rel="noopener" class="btn-primary" aria-label="Visit LinkedIn profile">Connect on LinkedIn</a>
    </section>

    <section id="about" aria-labelledby="about-title">
      <h2 id="about-title">About Me</h2>
      <div class="card">
        <p>
          I am a Cybersecurity and Full Stack Development enthusiast pursuing a Master’s in Cyber Forensics & Information Security. Skilled in Python, SQL, secure web development, encryption, digital forensics, and vulnerability assessment. I am actively building real-world projects through Nxtwave’s CCBP 4.0 program and eager to contribute technical skills in entry-level cybersecurity or software development roles.
        </p>
      </div>
    </section>

    <section id="education" aria-labelledby="education-title">
      <h2 id="education-title">Education</h2>
      <div class="grid-3">
        <div class="card" role="article" tabindex="0">
          <h3>M.Sc - Cyber Forensics & Information Security</h3>
          <p>Madras University, Chennai<br />07/2024 – 06/2026 (Ongoing)</p>
        </div>

        <div class="card" role="article" tabindex="0">
          <h3>B.C.A - Computer Applications</h3>
          <p>Madras University, Chennai<br />06/2020 – 06/2023</p>
        </div>

        <div class="card" role="article" tabindex="0">
          <h3>Full Stack Developer Program</h3>
          <p>Nxtwave CCBP 4.0 Academy, Chennai (Present)<br />
             Training on HTML, CSS, JavaScript, Node.js, Express, SQL, MongoDB, Git & GitHub, project building, and interview skills.</p>
        </div>
      </div>
    </section>

    <section id="skills" aria-labelledby="skills-title">
      <h2 id="skills-title">Skills</h2>
      <div class="grid-3">
        <div class="card" role="article" tabindex="0">
          <h3>Technical Skills</h3>
          <ul class="skills-list">
            <li>Python, SQL</li>
            <li>HTML, CSS, Bootstrap</li>
            <li>Digital Forensics, Penetration Testing (Basics)</li>
            <li>Incident Response, Vulnerability Assessment, Network Security</li>
            <li>Ethical Hacking (Basics), Linux, MySQL</li>
          </ul>
        </div>
        <div class="card" role="article" tabindex="0">
          <h3>Cybersecurity Concepts</h3>
          <ul class="skills-list">
            <li>Foundations of Cybersecurity</li>
            <li>CIA Triad (Confidentiality, Integrity, Availability)</li>
            <li>Assets, Threats, Vulnerabilities</li>
            <li>Risk Management & Threat Modeling</li>
            <li>Detection and Response, Incident Response</li>
            <li>Encryption & Hashing, Authentication Protocols</li>
          </ul>
        </div>
        <div class="card" role="article" tabindex="0">
          <h3>Soft Skills & Transferable Skills</h3>
          <ul class="skills-list">
            <li>Root-Cause Analysis & Issue Resolution</li>
            <li>Process Optimization & Technical Reporting</li>
            <li>Personality Development & Self-paced Learning</li>
            <li>Stakeholder Coordination & Team Leadership</li>
            <li>Time Management</li>
            <li>Managed site operations, client communications & teams</li>
            <li>Digitized manual billing and reporting using MS Excel & Word</li>
          </ul>
        </div>
      </div>
    </section>

    <section id="certificates" aria-labelledby="certificates-title">
      <h2 id="certificates-title">Certificates</h2>
      <div class="grid-3">
        <div class="card" tabindex="0">
          <h3>Google Cybersecurity Professional Specialization</h3>
          <p>Coursera</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Computer Network Security</h3>
          <p>EC-Council CodeRed</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Linux Essentials</h3>
          <p>EC-Council CodeRed</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Cryptanalysis in Action</h3>
          <p>EC-Council CodeRed</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Build Your Own Static Website</h3>
          <p>Nxtwave CCBP 4.0</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Build Your Own Responsive Website</h3>
          <p>Nxtwave CCBP 4.0</p>
        </div>
        <div class="card" tabindex="0">
          <h3>Introduction to Databases (SQL)</h3>
          <p>Nxtwave CCBP 4.0</p>
        </div>
      </div>
    </section>

    <section id="experience" aria-labelledby="experience-title">
      <h2 id="experience-title">Work Experience</h2>
      <div class="card" tabindex="0">
        <h3>General Manager</h3>
        <p>Ms Transport, Chennai (Present) - 5 Years Experience</p>
        <ul class="skills-list" style="margin-top: 0.5rem;">
          <li>Managed site operations, worker scheduling, and staff coordination across multiple locations.</li>
          <li>Handled accounts, workforce planning, and client coordination.</li>
          <li>Led a team of 15+ site workers and drivers, scheduling shifts and resolving conflicts.</li>
          <li>Digitized manual billing processes using Word, Excel to streamline reporting and reduce errors.</li>
          <li>Coordinated between clients, drivers, and field staff to ensure timely service delivery.</li>
          <li>Developed leadership, time management, and crisis-resolution skills through on-site operations.</li>
        </ul>
      </div>
    </section>

    <section id="contact" aria-labelledby="contact-title">
      <h2 id="contact-title">Contact</h2>
      <div class="contact-info" tabindex="0">
        <p>Phone: <a href="tel:+917358520585">+91 73585 20585</a></p>
        <p>Email: <a href="mailto:haisehkr@gmail.com">haisehkr@gmail.com</a></p>
        <p>LinkedIn: <a href="https://linkedin.com/in/s-harishkumar" target="_blank" rel="noopener">linkedin.com/in/s-harishkumar</a></p>
        <p>Location: Chennai, India</p>
        <p>Date of Birth: 04/12/2001</p>
      </div>
    </section>
  </main>

  <footer>
    &copy; 2024 Harish Kumar S. All rights reserved.
  </footer>
</body>
</html>

