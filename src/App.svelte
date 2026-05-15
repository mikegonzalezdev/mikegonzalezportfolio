<script>
  const certifications = [
    {
      name: "Taller Desarrollo de Aplicaciones en Python",
      year: "2025",
      url: "https://drive.google.com/your-link-python"
    },
    {
      name: "Servicio al Cliente — INA / Empleo+",
      year: "2026",
      url: "https://drive.google.com/your-link-ina"
    },
    {
      name: "Computación — Academia Siquirres (140 hrs)",
      year: "2019",
      url: "https://drive.google.com/your-link-computacion"
    }
  ]
</script>

<main>
  <!--HERO -->
  <header class="hero">
    <div class="hero-text">
      <p class="hero-label">Portafolio</p>
      <h1>Mike González</h1>
      <h2>Estudiante de Ingeniería en Sistemas Computacionales — UTC</h2>
      <p class="hero-sub">
        <strong>Segundo Cuatrimestre</strong> iniciado el 12 de mayo del 2026 &nbsp;·&nbsp;
        <strong>1</strong> de <strong>8</strong> cuatrimestres completados</p>
      <nav class="nav-links">
        <a class="link" href="https://api.whatsapp.com/send?phone=50662119161&text=¡Hola!%20Estoy%20interesado%20en%20tu%20portafolio." target="_blank" rel="noopener noreferrer">WhatsApp</a>
        <a class="link" href="https://github.com/mikegonzalezdev" target="_blank" rel="noopener noreferrer">GitHub</a>
        <a class="link" href="https://www.linkedin.com/in/mikegonzalez17/" target="_blank" rel="noopener noreferrer">LinkedIn</a>
      </nav>
    </div>
    <picture class="hero-img-wrap">
      <source srcset="/mikeyrandall.webp" type="image/webp">
      <img
        id="mikeyrandall"
        alt="Mike González con el Alcalde Siquirreño Randall Black Reid"
        src="/mikeyrandall.webp"
        width="800"
        height="600"
        fetchpriority="high"
        decoding="async">
    </picture>
  </header>

  <!-- STACK GRID -->
  <section class="section" aria-label="Stack tecnológico">
    <div class="skills-grid">

      <div class="category" style="contain: paint;">
        <h3 class="category-title">Lenguajes</h3>
        <ul class="tech-list">
          <li class="tech-item"><img src="/python.svg" width="32" height="32" alt="Python logo" loading="lazy"><span>Python <em class="badge">En progreso</em></span></li>
          <li class="tech-item"><img src="/c-plusplus.svg" width="32" height="32" alt="C++ logo" loading="lazy"><span>C++ <em class="badge">En progreso</em></span></li>
          <li class="tech-item"><img src="/html5.svg" width="32" height="32" alt="HTML5 logo" loading="lazy"><span>HTML</span></li>
          <li class="tech-item"><img src="/css.svg" width="32" height="32" alt="CSS logo" loading="lazy"><span>CSS</span></li>
          <li class="tech-item"><img src="/javascript.svg" width="32" height="32" alt="JavaScript logo" loading="lazy"><span>JavaScript</span></li>
        </ul>
      </div>

      <div class="category" style="contain: paint;">
        <h3 class="category-title">Frameworks</h3>
        <ul class="tech-list">
          <li class="tech-item"><img src="/svelte.svg" width="32" height="32" alt="Svelte logo" loading="lazy"><span>Svelte</span></li>
        </ul>
      </div>

      <div class="category" style="contain: paint;">
        <h3 class="category-title">Herramientas</h3>
        <ul class="tech-list">
          <li class="tech-item"><img src="/github.svg" width="32" height="32" alt="GitHub logo" loading="lazy"><span>Git / GitHub</span></li>
          <li class="tech-item"><img src="/vscode.svg" width="32" height="32" alt="Visual Studio Code logo" loading="lazy"><span>Visual Studio Code</span></li>
          <li class="tech-item"><img src="/pycharm.svg" width="32" height="32" alt="PyCharm logo" loading="lazy"><span>PyCharm</span></li>
          <li class="tech-item"><img src="/terminalubuntu.svg" width="32" height="32" alt="Terminal Unix logo" loading="lazy"><span>Terminal (Unix)</span></li>
          <li class="tech-item"><img src="/Ollama_light.svg" width="32" height="32" alt="Ollama logo" loading="lazy"><span>Ollama</span></li>
        </ul>
      </div>

    </div>
  </section>

  <!-- EXPERIENCIA -->
  <section class="section" aria-label="Experiencia">
    <h2 class="section-title">Experiencia</h2>
    <div class="card-grid" style="contain: paint;">

      <article class="card card--accent">
        <h3>Apple Developer & Public Beta Program</h3>
        <p>Reporte de más de <strong>558 bugs</strong> en iOS y macOS con logs, pasos reproducibles y evidencia técnica. Más de 2 años de participación activa.</p>
        <span class="card-tag">QA · iOS · macOS</span>
      </article>

      <article class="card">
        <h3>Chatbot WhatsApp — ALIARSE</h3>
        <p>Desarrollo con Python y Ollama: integración CSV, Tool Calling, System Prompts y Guardrails. Proyecto académico, Feb. 2026.</p>
        <span class="card-tag">Python · LLM · Ollama</span>
      </article>

      <article class="card">
        <h3>Traductor e Intérprete — Boëna Lodge</h3>
        <p>Traducción simultánea Inglés–Español para turistas en tours de naturaleza. Comunicación técnica en entornos de alta exigencia. 2024–Presente.</p>
        <span class="card-tag">Inglés B2 · Servicio</span>
      </article>

      <article class="card">
        <h3>Asistente de Enseñanza — Escuela Virtual</h3>
        <p>Colaborador creativo en Escuela Virtual de Inglés Rosalía Brown Young, orientada a niños. Tutorías privadas de Inglés Técnico/Conversacional.</p>
        <span class="card-tag">Inglés · Enseñanza</span>
      </article>

    </div>
  </section>

  <!-- HABILIDADES + LOGROS -->
  <section class="section two-col" aria-label="Habilidades y logros">

    <div>
      <h2 class="section-title">Habilidades</h2>
      <div class="pill-grid" style="contain: paint;">
        <span class="pill">QA & Aseguramiento de Calidad</span>
        <span class="pill">Documentación técnica de bugs</span>
        <span class="pill">Modelos de lenguaje local (LLMs)</span>
        <span class="pill">Speculative Decoding</span>
        <span class="pill">Diagnóstico de problemas</span>
        <span class="pill">Inglés B2 — Bilingüe</span>
        <span class="pill">macOS / iOS Avanzado</span>
        <span class="pill">Linux (Aprendiendo)</span>
      </div>
    </div>

    <div>
      <h2 class="section-title">Logros</h2>
      <ul class="achievement-list" style="contain: paint;">
        <li>
          <span class="ach-num">558+</span>
          <span class="ach-text">bugs reportados a Apple con evidencia técnica completa</span>
        </li>
        <li>
          <span class="ach-num">3</span>
          <span class="ach-text">años consecutivos de Excelencia Académica en Inglés (2023–2025)</span>
        </li>
        <li>
          <span class="ach-text">Reconocimiento firmado por el Alcalde Randall Black Reid</span>
        </li>
        <li>
          <span class="ach-text">Chatbot funcional para WhatsApp con Tool Calling — ALIARSE 2026</span>
        </li>
      </ul>
    </div>

  </section>

  <!-- ESTUDIOS -->
  <section class="section" aria-label="Estudios">
    <h2 class="section-title">Estudios</h2>
    <ol class="timeline" style="contain: paint;">
      <li class="timeline-item timeline-item--active">
        <span class="tl-year">2026–Hoy</span>
        <div class="tl-body">
          <strong>Bachillerato en Ingeniería en Sistemas Computacionales</strong>
          <span>Universidad Tecnológica Costarricense (UTC)</span>
        </div>
      </li>
      <li class="timeline-item">
        <span class="tl-year">Dic. 2025</span>
        <div class="tl-body">
          <strong>Bachillerato en Educación Media</strong>
          <span>Liceo Tres Equis, Turrialba</span>
        </div>
      </li>
      <li class="timeline-item">
        <span class="tl-year">2022–2023</span>
        <div class="tl-body">
          <strong>CTP Padre Roberto Evans Saunders</strong>
          <span>Siquirres — 1 año y 6 meses</span>
        </div>
      </li>
      <li class="timeline-item">
        <span class="tl-year">Primaria</span>
        <div class="tl-body">
          <strong>Escuela La Amelia</strong>
          <span>Siquirres</span>
        </div>
      </li>
    </ol>
  </section>

  <!-- CERTIFICACIONES -->
  <section class="section" aria-label="Certificaciones">
    <h2 class="section-title">Cursos y Certificaciones</h2>
    <ul class="cert-list" style="contain: paint;">
      {#each certifications as cert}
        <li>
          <a class="cert-item" href={cert.url} target="_blank" rel="noopener noreferrer">
            <span class="cert-icon">↗</span>
            <span class="cert-info">
              <strong>{cert.name}</strong>
              <span class="cert-year">{cert.year}</span>
            </span>
          </a>
        </li>
      {/each}
    </ul>
  </section>

  <!-- FAQ -->
  <section class="section" aria-label="Preguntas frecuentes">
    <h2 class="section-title">Preguntas frecuentes</h2>
    <div class="faq-grid" style="contain: paint;">
      <details class="faq-item">
        <summary>¿Cuántos bugs has reportado?</summary>
        <p>Más de 558 reportes enviados a Apple en los programas Developer y Public Beta de iOS y macOS, con logs, capturas y pasos de reproducción detallados.</p>
      </details>
      <details class="faq-item">
        <summary>¿Qué estudios tienes?</summary>
        <p>CTP Padre Roberto Evans Saunders, Liceo Tres Equis, Academia Siquirres, Escuela Virtual de Inglés Rosalía Brown Young, y actualmente UTC.</p>
      </details>
      <details class="faq-item">
        <summary>¿Dónde te ubicas?</summary>
        <p>Cerca de Siquirres y Turrialba, Costa Rica.</p>
      </details>
      <details class="faq-item">
        <summary>¿Cuál es tu lenguaje favorito?</summary>
        <p>Python y HTML — Python por su versatilidad, HTML por ser la base de todo lo que construyo.</p>
      </details>
      <details class="faq-item">
        <summary>¿Modalidad de trabajo preferida?</summary>
        <p>Remoto preferiblemente, aunque puedo presencial si es requerido.</p>
      </details>
    </div>
  </section>

  <footer class="site-footer">
    <small>Copyright © 2026 — Portfolio de Mike González</small>
    <small class="wip">Página en construcción, mejorando continuamente.</small>
  </footer>
</main>

<style>
  /* ── Variables ── */
  :root {
    --accent: #3f9ab5;
    --accent-hover: #00ccff;
    --bg: #ffffff;
    --bg2: #f4f4f2;
    --bg3: #eaeaea;
    --text: #1a1a1a;
    --text-muted: #555;
    --border: rgba(0,0,0,0.08);
    --card-bg: #ffffff;
    --card-border: rgba(0,0,0,0.07);
    --radius: 24px;
    --radius-sm: 24px;
  }
  @media (prefers-color-scheme: dark) {
    :root {
      --bg: #141414;
      --bg2: #1c1c1c;
      --bg3: #252525;
      --text: #ececec;
      --text-muted: #999;
      --border: rgba(255,255,255,0.08);
      --card-bg: #1e1e1e;
      --card-border: rgba(255,255,255,0.07);
    }
  }

  /* ── Reset / Base ── */
  * { box-sizing: border-box; }
  main {
    max-width: 900px;
    margin: 0 auto;
    padding: 2rem 1.25rem 4rem;
    color: var(--text);
  }
  h1, h2, h3 { margin: 0; font-weight: 700; }
  ul, ol { margin: 0; padding: 0; list-style: none; }

  /* ── Hero ── */
  .hero {
    display: flex;
    align-items: center;
    gap: 2.5rem;
    padding: 2.5rem 0 3rem;
    flex-wrap: wrap;
  }
  .hero-text { flex: 1; min-width: 260px; }
  .hero-label {
    font-size: 0.75rem;
    font-weight: 600;
    letter-spacing: .12em;
    text-transform: uppercase;
    color: var(--accent);
    margin: 0 0 .5rem;
  }
  .hero h1 {
    font-size: clamp(2rem, 5vw, 3rem);
    line-height: 1.05;
    margin-bottom: .4rem;
  }
  .hero h2 {
    font-size: 1rem;
    font-weight: 400;
    color: var(--text-muted);
    margin-bottom: .75rem;
  }
  .hero-sub {
    font-size: .9rem;
    color: var(--text-muted);
    margin: 0 0 1.5rem;
  }
  .hero-img-wrap {
    flex-shrink: 0;
    contain: paint;
  }
  .hero-img-wrap img {
    width: 220px;
    height: auto;
    border-radius: var(--radius);
    display: block;
    object-fit: cover;
  }

  /* ── Nav links ── */
  .nav-links { display: flex; gap: .75rem; flex-wrap: wrap; }
  .link {
    color: var(--accent);
    text-decoration: none;
    font-weight: 600;
    font-size: .875rem;
    padding: .45rem 1rem;
    border-radius: 9999px;
    border: 1.5px solid var(--accent);
    background: transparent;
    transition: color .2s ease, border-color .2s ease, background .2s ease, transform .2s ease;
    will-change: transform;
    transform: translateZ(0);
  }
  .link:hover {
    color: var(--accent-hover);
    border-color: var(--accent-hover);
    background: rgba(0,204,255,.07);
    transform: translateY(-2px);
  }

  /* ── Sections ── */
  .section { margin-bottom: 3.5rem; }
  .section-title {
    font-size: 1.1rem;
    font-weight: 700;
    letter-spacing: .04em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 1.25rem;
    padding-bottom: .5rem;
    border-bottom: 1px solid var(--border);
  }
  .two-col {
    display: grid;
    grid-template-columns: 1fr 1fr;
    gap: 3rem;
  }
  @media (max-width: 640px) {
    .two-col { grid-template-columns: 1fr; gap: 2rem; }
    .hero { flex-direction: column-reverse; }
    .hero-img-wrap img { width: 100%; max-width: 320px; }
  }

  /* ── Skills Grid ── */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
    gap: 1.25rem;
  }
  .category {
    background: var(--bg3);
    border-radius: var(--radius);
    padding: 1.5rem;
    border: 1px solid var(--card-border);
  }
  .category-title {
    font-size: .85rem;
    font-weight: 700;
    letter-spacing: .08em;
    text-transform: uppercase;
    color: var(--accent);
    margin-bottom: 1rem;
    display: flex;
    align-items: center;
    gap: .4rem;
  }
  .tech-item {
  display: flex;
  align-items: center;
  gap: 0.6rem;
}
.tech-list {
  display: flex;
  flex-direction: column;
  gap: 0.6rem;
}
  .tech-item img { flex-shrink: 0; }
  .badge {
    font-size: .7rem;
    font-style: normal;
    font-weight: 600;
    background: rgba(63,154,181,.15);
    color: var(--accent);
    padding: 1px 6px;
    border-radius: 4px;
    margin-left: .25rem;
  }

  /* ── Experience Cards ── */
  .card-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(260px, 1fr));
    gap: 1rem;
  }
  .card {
    background: var(--card-bg);
    border: 1px solid var(--card-border);
    border-radius: var(--radius);
    padding: 1.5rem;
    display: flex;
    flex-direction: column;
    gap: .6rem;
    transition: transform .2s ease, box-shadow .2s ease;
    will-change: transform;
    transform: translateZ(0);
  }
  .card:hover {
    transform: translateY(-3px);
    box-shadow: 0 8px 24px rgba(0,0,0,.08);
  }
  .card--accent { border-left: 3px solid var(--accent); }
  .card h3 {
    font-size: 1rem;
    font-weight: 700;
    color: var(--text);
  }
  .card p {
    font-size: .875rem;
    color: var(--text-muted);
    line-height: 1.6;
    margin: 0;
  }
  .card-tag {
    font-size: .72rem;
    font-weight: 600;
    letter-spacing: .06em;
    color: var(--accent);
    margin-top: auto;
    padding-top: .5rem;
  }

  /* ── Pill Grid (Habilidades) ── */
  .pill-grid {
    display: flex;
    flex-wrap: wrap;
    gap: .5rem;
  }
  .pill {
    font-size: .8rem;
    font-weight: 500;
    padding: .35rem .85rem;
    border-radius: 9999px;
    background: var(--bg3);
    border: 1px solid var(--card-border);
    color: var(--text);
  }

  /* ── Achievement List ── */
  .achievement-list { display: flex; flex-direction: column; gap: 1rem; }
  .achievement-list li {
    display: flex;
    align-items: flex-start;
    gap: 1rem;
  }
  .ach-num {
    font-size: 1.4rem;
    font-weight: 800;
    color: var(--accent);
    min-width: 48px;
    line-height: 1.2;
    flex-shrink: 0;
  }
  .ach-text {
    font-size: .875rem;
    color: var(--text-muted);
    line-height: 1.5;
    padding-top: .2rem;
  }

  /* ── Estudios/Linea de Tiempo── */
  .timeline { display: flex; flex-direction: column; gap: 0; }
  .timeline-item {
    display: flex;
    gap: 1.25rem;
    padding: 0.90rem 0;
    border-left: 4px solid var(--border);
    padding-left: 1.5rem;
    position: relative;
  }
  .timeline-item::before {
  content: '';
  position: absolute;
  left: -5px;
  top: 1.25rem;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background: var(--border);
  border: 2px solid var(--bg);
  }
  .timeline-item--active { border-left-color: var(--accent); }
  .timeline-item--active::before { background: var(--accent); }
  .tl-year {
    font-size: .75rem;
    font-weight: 700;
    color: var(--accent);
    min-width: 72px;
    padding-top: .1rem;
    flex-shrink: 0;
  }
  .tl-body {
    display: flex;
    flex-direction: column;
    gap: .2rem;
  }
  .tl-body strong { font-size: .95rem; color: var(--text); }
  .tl-body span { font-size: .8rem; color: var(--text-muted); }

  /* ── Certifications ── */
  .cert-list { display: flex; flex-direction: column; gap: .6rem; }
  .cert-item {
  display: flex;
  align-items: flex-start;
  gap: 1rem;
  padding: .9rem 1.1rem;
  background: var(--bg3);
  border: 1px solid var(--card-border);
  border-radius: var(--radius-sm);
  text-decoration: none;
  color: var(--text);
  transition: background .15s ease, transform .15s ease;
  will-change: transform;
  transform: translateZ(0);
}
  .cert-item:hover {
    background: var(--bg2);
  }
  .cert-icon {
    font-size: 1rem;
    color: var(--accent);
    flex-shrink: 0;
  }
  .cert-info {
  display: flex;
  flex-direction: column;
  gap: .15rem;
  flex: 1;
  text-align: left;
  }
  .cert-info strong { font-size: .9rem; }
  .cert-year {
  font-size: .75rem;
  color: var(--text-muted);
  display: block;
  text-align: left;
  }
  /* ── FAQ ── */
  .faq-grid { display: flex; flex-direction: column; gap: .5rem; }
  .faq-item {
    background: var(--bg3);
    border: 1px solid var(--card-border);
    border-radius: var(--radius-sm);
    overflow: hidden;
  }
  .faq-item summary {
    padding: .9rem 1.1rem;
    font-weight: 600;
    font-size: .9rem;
    cursor: pointer;
    list-style: none;
    display: flex;
    justify-content: space-between;
    align-items: center;
    color: var(--text);
  }
  .faq-item summary::-webkit-details-marker { display: none; }
  .faq-item summary::after {
    content: '+';
    font-size: 1.2rem;
    color: var(--accent);
    transition: transform .2s ease;
  }
  .faq-item[open] summary::after { transform: rotate(45deg); }
  .faq-item p {
    padding: 0 1.1rem 1rem;
    font-size: .875rem;
    color: var(--text-muted);
    line-height: 1.6;
    margin: 0;
  }
  /* ──Footer── */
  .site-footer {
    margin-top: 4rem;
    padding-top: 1.5rem;
    border-top: 1px solid var(--border);
    display: flex;
    flex-direction: column;
    gap: .25rem;
    font-size: .8rem;
    color: var(--text-muted);
    text-align: center;
  }
  .wip { opacity: .6; }
</style>