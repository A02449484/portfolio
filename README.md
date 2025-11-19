<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Your Name – Design & Games</title>
  <meta name="description" content="Designer and game developer – portfolio, resume, and contact."/>

  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;500;600;700&display=swap" rel="stylesheet">

  <style>
    :root {
      --bg: #0f0f12;
      --text: #e0e0e0;
      --accent: #a78bfa;
      --light: #bbbbbb;
    }
    * { margin:0; padding:0; box-sizing:border-box; }
    body {
      background: var(--bg);
      color: var(--text);
      font-family: 'Inter', system-ui, sans-serif;
      line-height: 1.6;
      padding: 0 1rem;
    }
    header, main, footer { max-width: 840px; margin: 0 auto; }
    header { padding: 4rem 0 2rem; text-align: center; }
    h1 { font-size: 2.8rem; font-weight: 700; color: white; margin-bottom: 0.5rem; }
    h2 { font-size: 2rem; font-weight: 600; color: var(--accent); margin: 3rem 0 1.5rem; }
    h3 { font-size: 1.4rem; margin: 1.5rem 0 0.8rem; color: white; }
    p, li { font-size: 1.1rem; color: var(--light); margin-bottom: 1rem; }
    a { color: var(--accent); text-decoration: none; }
    a:hover { text-decoration: underline; }
    ul { padding-left: 1.5rem; }
    section { padding: 2rem 0; }
    .grid {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(280px, 1fr));
      gap: 2rem;
      margin-top: 2rem;
    }
    .project {
      background: #1a1a1e;
      border-radius: 12px;
      overflow: hidden;
    }
    .project img {
      width: 100%;
      height: 200px;
      object-fit: cover;
      display: block;
    }
    .project div {
      padding: 1.2rem;
    }
    footer { text-align: center; padding: 4rem 0 2rem; font-size: 0.9rem; color: #666; }
    @media (max-width: 600px) {
      h1 { font-size: 2.2rem; }
      h2 { font-size: 1.7rem; }
    }
  </style>
</head>
<body>

  <header>
    <h1>Your Name</h1>
    <p>Designer × Game Developer</p>
  </header>

  <main>

    <!-- HOME / ABOUT -->
    <section id="about">
      <h2>Hey, I'm Your Name</h2>
      <p>
        I make games and interactive experiences that feel good to look at and play.
        I care a lot about clean UI, thoughtful animation, and systems that are fun to tinker with.
      </p>
      <p>
        Currently looking for new opportunities (full-time, contract, or interesting indie collaborations).
      </p>
    </section>

    <!-- RESUME -->
    <section id="resume">
      <h2>Resume</h2>

      <h3>Focus</h3>
      <p>UI/UX Design • Game Design • Prototyping • Unity / Godot • Pixel Art & Vector Illustration</p>

      <h3>Experience</h3>
      <ul>
        <li><strong>Game Designer & UI Artist</strong> – Studio Name (2022–2024)<br>Designed core loops, UI flows, and marketing assets for two released mobile titles.</li>
        <li><strong>Freelance Designer</strong> – 2019–Present<br>Branding, UI kits, and game prototypes for indie devs and startups.</li>
        <!-- Add or remove lines as needed -->
      </ul>

      <h3>Education</h3>
      <ul>
        <li>B.A. Interactive Arts & Media – Some University (2018–2022)</li>
      </ul>

      <p><a href="your-resume.pdf" target="_blank">↓ Download full resume (PDF)</a></p>
    </section>

    <!-- COVER LETTER (short) -->
    <section id="cover">
      <h2>Cover Letter</h2>
      <p>
        I love building things that are playful but polished. Whether it’s a cozy puzzle game or a sleek tool, I’m happiest when the details feel right and the player/user smiles.
      </p>
      <p>
        I’m especially interested in small-to-medium teams where I can wear multiple hats (design, UI, light code, marketing art). Remote is ideal, but I’m open to relocating for the right project.
      </p>
      <p>Let’s make something cool together.</p>
    </section>

    <!-- PORTFOLIO -->
    <section id="portfolio">
      <h2>Selected Work</h2>

      <div class="grid">
        <!-- Repeat this block for each project -->
        <div class="project">
          <img src="https://via.placeholder.com/600x400/333/fff?text=Project+1" alt="Project screenshot">
          <div>
            <h3>Project Title 1</h3>
            <p>Short one-sentence description. Tools: Unity, Aseprite, Figma.</p>
          </div>
        </div>

        <div class="project">
          <img src="https://via.placeholder.com/600x400/333/fff?text=Project+2" alt="Project screenshot">
          <div>
            <h3>Project Title 2</h3>
            <p>Another quick line. Role: UI/UX + pixel art.</p>
          </div>
        </div>

        <!-- Add more projects here -->
      </div>

      <p style="margin-top: 2rem;">
        <a href="https://itch.io/yourname" target="_blank">More on itch.io</a> •
        <a href="https://artstation.com/yourname" target="_blank">ArtStation</a>
      </p>
    </section>

    <!-- CONTACT -->
    <section id="contact">
      <h2>Contact & Links</h2>
      <p>
        <a href="mailto:you@email.com">you@email.com</a><br><br>
        <a href="https://twitter.com/yourhandle" target="_blank">Twitter</a> •
        <a href="https://linkedin.com/in/yourname" target="_blank">LinkedIn</a> •
        <a href="https://github.com/yourname" target="_blank">GitHub</a> •
        <a href="https://instagram.com/yourname" target="_blank">Instagram</a>
      </p>
    </section>

  </main>

  <footer>
    © 2025 Your Name — Made with a keyboard and too much coffee
  </footer>

</body>
</html>
