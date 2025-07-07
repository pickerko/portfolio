<!DOCTYPE html>
<html lang="sk">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Pickerko – Web Developer</title>
  <style>
    * { box-sizing: border-box; margin: 0; padding: 0; }
    body {
      font-family: 'Segoe UI', sans-serif;
      background: #f7f9fc;
      color: #333;
      line-height: 1.6;
    }
    header {
      background: #0077cc;
      color: white;
      padding: 2rem;
      text-align: center;
    }
    header h1 { font-size: 2.5rem; }
    header p { margin-top: 0.5rem; }

    section {
      max-width: 800px;
      margin: 2rem auto;
      padding: 0 1rem;
    }

    h2 {
      margin-bottom: 1rem;
      color: #0077cc;
    }

    .projects {
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 1rem;
    }

    .project {
      background: white;
      border-radius: 8px;
      padding: 1rem;
      box-shadow: 0 4px 12px rgba(0,0,0,0.05);
    }

    .project h3 { margin-bottom: 0.5rem; }

    footer {
      text-align: center;
      padding: 2rem 1rem;
      background: #eaeaea;
      margin-top: 2rem;
    }

    a {
      color: #0077cc;
      text-decoration: none;
    }

    @media (max-width: 700px) {
      .projects {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Ahoj, som Pickerko</h1>
    <p>Začínajúci web developer – tvorím jednoduché a čisté weby</p>
  </header>

  <section>
    <h2>O mne</h2>
    <p>
      Učím sa HTML, CSS a JavaScript. Mám rád čistý dizajn a funkčné weby.
      Každý deň sa zlepšujem a hľadám príležitosti, kde môžem pomôcť klientom s ich online prezentáciou.
    </p>
  </section>

  <section>
    <h2>Projekty</h2>
    <div class="projects">
      <div class="project">
        <h3>Stránka O mne</h3>
        <p>Moja prvá webstránka – jednoduchý HTML projekt s GitHub Pages.</p>
        <a href="https://pickerko.github.io/about-me" target="_blank">Zobraziť stránku</a>
      </div>
      <!-- Môžeš pridať ďalší projekt -->
      <!--
      <div class="project">
        <h3>Názov projektu</h3>
        <p>Popis projektu...</p>
        <a href="#">Zobraziť</a>
      </div>
      -->
    </div>
  </section>

  <section>
    <h2>Kontakt</h2>
    <p>
      📧 <a href="mailto:tvojemail@gmail.com">tvojemail@gmail.com</a><br/>
      💻 <a href="https://github.com/pickerko" target="_blank">GitHub profil</a>
    </p>
  </section>

  <footer>
    &copy; 2025 Pickerko – Všetky práva vyhradené
  </footer>
</body>
</html>
