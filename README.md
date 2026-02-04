# Nordintel.no
nordintel-website/
  index.html
  assets/
    css/
      style.css
    js/
      main.js
  README.md
<!doctype html>
<html lang="no">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <title>Nordintel | Rimelige nettsider for lokale bedrifter</title>
    <meta
      name="description"
      content="Nordintel lager rimelige, mobilvennlige nettsider for små og mellomstore bedrifter i Bodø. Vi kombinerer AI og personlig oppfølging."
    />
    <meta name="theme-color" content="#0b1220" />

    <link rel="preconnect" href="https://fonts.googleapis.com" />
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin />
    <link
      href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;700&display=swap"
      rel="stylesheet"
    />

    <link rel="stylesheet" href="assets/css/style.css" />
    <link rel="icon" href="data:," />
  </head>

  <body>
    <a class="skip-link" href="#main">Hopp til innhold</a>

    <header class="site-header" data-header>
      <div class="container header-inner">
        <a class="brand" href="#top" aria-label="Nordintel hjem">
          <span class="brand-mark" aria-hidden="true">NI</span>
          <span class="brand-name">Nordintel</span>
        </a>

        <nav class="nav" aria-label="Hovedmeny">
          <button class="nav-toggle" type="button" aria-expanded="false" aria-controls="navMenu" data-nav-toggle>
            Meny
          </button>
          <ul id="navMenu" class="nav-list" data-nav-menu>
            <li><a href="#tjenester">Tjenester</a></li>
            <li><a href="#slik-jobber-vi">Slik jobber vi</a></li>
            <li><a href="#priser">Priser</a></li>
            <li><a href="#team">Team</a></li>
            <li><a class="btn btn-small" href="#kontakt">Kontakt</a></li>
          </ul>
        </nav>
      </div>
    </header>

    <main id="main">
      <section id="top" class="hero">
        <div class="container hero-grid">
          <div class="hero-content">
            <p class="eyebrow">Nettsider for små og mellomstore bedrifter i :contentReference[oaicite:0]{index=0}</p>
            <h1>Rimelige nettsider som ser bra ut og funker på mobil</h1>
            <p class="lead">
              Nordintel lager enkle og profesjonelle nettsider for bedrifter som trenger bedre synlighet på nett.
              Vi bruker AI for å jobbe effektivt, men vi følger deg opp personlig hele veien.
            </p>

            <div class="hero-cta">
              <a class="btn" href="#kontakt">Få gratis prat</a>
              <a class="btn btn-ghost" href="#tjenester">Se hva vi tilbyr</a>
            </div>

            <ul class="trust-list" aria-label="Høydepunkter">
              <li>Mobilvennlig design</li>
              <li>Rask levering</li>
              <li>Tilpasset bedriften din</li>
              <li>Fleksibel pris</li>
            </ul>
          </div>

          <div class="hero-card" aria-label="Eksempel på hva dere får">
            <div class="card">
              <h2 class="card-title">Det du får</h2>
              <ul class="checklist">
                <li>Forside med tydelig budskap</li>
                <li>Kontakt og kartlenke</li>
                <li>Tjenestesider</li>
                <li>Enkel redigerbar tekst</li>
                <li>Grunnleggende SEO</li>
              </ul>
              <p class="card-note">
                Vi avtaler innhold og pris direkte med deg, så du slipper dyre pakker du ikke trenger.
              </p>
            </div>
          </div>
        </div>
      </section>

      <section id="tjenester" class="section">
        <div class="container">
          <header class="section-header">
            <h2>Tjenester</h2>
            <p>
              Vi lager nettsider som er enkle å bruke, og som gjør at kunder faktisk finner deg.
              Alt tilpasses behovet ditt.
            </p>
          </header>

          <div class="grid cards">
            <article class="card">
              <h3>Ny nettside</h3>
              <p>Perfekt for bedrifter som ikke har nettside, eller som vil starte på nytt.</p>
              <ul class="bullet">
                <li>Moderne design</li>
                <li>Mobil og nettbrett</li>
                <li>Rask lastetid</li>
              </ul>
            </article>

            <article class="card">
              <h3>Oppgradering</h3>
              <p>Vi forbedrer en gammel nettside med nytt design, tydelig struktur og bedre tekst.</p>
              <ul class="bullet">
                <li>Mer profesjonelt uttrykk</li>
                <li>Bedre oversikt for kunder</li>
                <li>Ryddig kontakt</li>
              </ul>
            </article>

            <article class="card">
              <h3>Synlighet</h3>
              <p>Grunnleggende SEO og struktur som gjør at du kan bli lettere å finne lokalt.</p>
              <ul class="bullet">
                <li>Riktige titler og beskrivelser</li>
                <li>Enkel sidekart struktur</li>
                <li>Tekst som faktisk forklarer hva dere gjør</li>
              </ul>
            </article>
          </div>
        </div>
      </section>

      <section id="slik-jobber-vi" class="section section-alt">
        <div class="container">
          <header class="section-header">
            <h2>Slik jobber vi</h2>
            <p>En enkel prosess. Du skal slippe å kunne mye teknisk for å få en bra nettside.</p>
          </header>

          <ol class="steps">
            <li>
              <h3>Gratis kartlegging</h3>
              <p>Vi prater om hva bedriften din trenger, målgruppe og hva dere vil oppnå.</p>
            </li>
            <li>
              <h3>Forslag og design</h3>
              <p>Vi lager et utkast raskt ved hjelp av AI og justerer etter tilbakemeldingene dine.</p>
            </li>
            <li>
              <h3>Bygging og innhold</h3>
              <p>Vi setter opp sider, tekst, bilder og struktur. Alt skal være lett å forstå.</p>
            </li>
            <li>
              <h3>Publisering og støtte</h3>
              <p>Vi publiserer nettsiden og sørger for at kontakt og info er lett å finne.</p>
            </li>
          </ol>
        </div>
      </section>

      <section id="priser" class="section">
        <div class="container">
          <header class="section-header">
            <h2>Priser</h2>
            <p>
              Vi bruker ikke faste pakker. Prisen avtales med hver kunde, basert på hvor stor nettsiden skal være.
              Det gjør at små bedrifter kan få en løsning som passer budsjettet.
            </p>
          </header>

          <div class="grid pricing">
            <article class="card">
              <h3>Enkel start</h3>
              <p class="price-hint">For små bedrifter som vil ha en ryddig og tydelig side.</p>
              <ul class="checklist">
                <li>Forside</li>
                <li>Tjenester</li>
                <li>Kontakt</li>
              </ul>
            </article>

            <article class="card highlight">
              <h3>Vanlig løsning</h3>
              <p class="price-hint">For bedrifter som vil forklare mer og få bedre struktur.</p>
              <ul class="checklist">
                <li>Flere undersider</li>
                <li>Bedre synlighet lokalt</li>
                <li>Mer innhold og seksjoner</li>
              </ul>
            </article>

            <article class="card">
              <h3>Skreddersydd</h3>
              <p class="price-hint">For deg som trenger spesielle sider eller ekstra funksjoner.</p>
              <ul class="checklist">
                <li>Egne behov</li>
                <li>Tilpasset design</li>
                <li>Ekstra oppfølging</li>
              </ul>
            </article>
          </div>

          <div class="note">
            <p>
              Vi kan gi et prisestimat etter en kort prat. Målet er at du skal få mest mulig for pengene.
            </p>
          </div>
        </div>
      </section>

      <section id="team" class="section section-alt">
        <div class="container">
          <header class="section-header">
            <h2>Team</h2>
            <p>
              Fire elever som jobber tett sammen. Vi får også veiledning av mentor Espen Rokkan i :contentReference[oaicite:1]{index=1}.
            </p>
          </header>

          <div class="grid team">
            <article class="card person">
              <h3>Johannes</h3>
              <p class="role">Daglig leder</p>
              <p>Holder oversikt og sørger for at vi leverer det vi lover.</p>
            </article>

            <article class="card person">
              <h3>Isak</h3>
              <p class="role">Økonomi</p>
              <p>Priser, avtaler og orden i tallene.</p>
            </article>

            <article class="card person">
              <h3>Julian</h3>
              <p class="role">Markedsføring og media</p>
              <p>Innhold, bilder og synlighet på sosiale medier.</p>
            </article>

            <article class="card person">
              <h3>Fredrik</h3>
              <p class="role">Salg og kundekontakt</p>
              <p>Første kontakt, oppfølging og dialog med kundene.</p>
            </article>
          </div>
        </div>
      </section>

      <section class="section">
        <div class="container">
          <header class="section-header">
            <h2>Hvorfor velge Nordintel</h2>
            <p>Vi kombinerer teknologi og menneskelig oppfølging, og vi jobber lokalt.</p>
          </header>

          <div class="grid cards">
            <article class="card">
              <h3>AI som sparer tid</h3>
              <p>Vi bruker AI for å jobbe raskere og holde prisen nede, men vi kvalitetssjekker alltid.</p>
            </article>
            <article class="card">
              <h3>Personlig service</h3>
              <p>Du får direkte kontakt med oss. Vi forklarer ting enkelt og følger deg opp.</p>
            </article>
            <article class="card">
              <h3>Lokalt fokus</h3>
              <p>Vi kjenner markedet her, og det gjør det lettere å lage en side som passer kundene dine.</p>
            </article>
          </div>
        </div>
      </section>

      <section id="kontakt" class="section section-alt">
        <div class="container">
          <header class="section-header">
            <h2>Kontakt oss</h2>
            <p>
              Send en melding, så tar vi en kort prat. Du kan også bruke e post eller telefon om du vil.
            </p>
          </header>

          <div class="grid contact">
            <form class="card form" id="contactForm" novalidate>
              <div class="field">
                <label for="name">Navn</label>
                <input id="name" name="name" type="text" autocomplete="name" required />
                <small class="error" data-error-for="name"></small>
              </div>

              <div class="field">
                <label for="email">E post</label>
                <input id="email" name="email" type="email" autocomplete="email" required />
                <small class="error" data-error-for="email"></small>
              </div>

              <div class="field">
                <label for="company">Bedrift</label>
                <input id="company" name="company" type="text" autocomplete="organization" />
              </div>

              <div class="field">
                <label for="message">Hva trenger du?</label>
                <textarea id="message" name="message" rows="6" required></textarea>
                <small class="error" data-error-for="message"></small>
              </div>

              <button class="btn" type="submit">Send forespørsel</button>
              <p class="form-note" id="formNote" role="status" aria-live="polite"></p>
              <p class="form-note">
                Dette skjemaet åpner e postklienten din med ferdig tekst. Hvis du vil bruke en ekte backend senere, kan vi legge det til.
              </p>
            </form>

            <aside class="card info">
              <h3>Kontaktinfo</h3>
              <ul class="info-list">
                <li><span>Sted:</span> Bodø</li>
                <li><span>E post:</span> <a href="mailto:kontakt@nordintel.no">kontakt@nordintel.no</a></li>
                <li><span>Telefon:</span> <a href="tel:+47XXXXXXXX">+47 XX XX XX XX</a></li>
              </ul>

              <div class="mini-faq">
                <h4>Vanlige spørsmål</h4>
                <details>
                  <summary>Hvor fort kan dere levere?</summary>
                  <p>Det kommer an på størrelse, men vi kan ofte levere et utkast raskt.</p>
                </details>
                <details>
                  <summary>Må jeg kunne noe teknisk?</summary>
                  <p>Nei. Vi forklarer enkelt og hjelper deg med alt.</p>
                </details>
                <details>
                  <summary>Kan dere bruke mitt innhold?</summary>
                  <p>Ja. Vi kan også hjelpe med tekstforslag og struktur.</p>
                </details>
              </div>
            </aside>
          </div>
        </div>
      </section>
    </main>

    <footer class="site-footer">
      <div class="container footer-inner">
        <p>© <span id="year"></span> Nordintel. Alle rettigheter reservert.</p>
        <p class="footer-links">
          <a href="#top">Til toppen</a>
          <a href="#kontakt">Kontakt</a>
        </p>
      </div>
    </footer>

    <script src="assets/js/main.js"></script>
  </body>
</html>
:root {
  --bg: #0b1220;
  --surface: #111a2e;
  --surface-2: #0f1730;
  --text: #e8ecf5;
  --muted: #b7c0d6;
  --line: rgba(255, 255, 255, 0.12);
  --accent: #4cc3ff;
  --accent-2: #7cf7c6;

  --radius: 16px;
  --shadow: 0 10px 30px rgba(0, 0, 0, 0.35);
  --max: 1100px;
}

* {
  box-sizing: border-box;
}

html {
  scroll-behavior: smooth;
}

body {
  margin: 0;
  font-family: Inter, system-ui, -apple-system, Segoe UI, Roboto, Arial, sans-serif;
  background: radial-gradient(1000px 500px at 20% 0%, rgba(76, 195, 255, 0.16), transparent 60%),
    radial-gradient(900px 500px at 80% 20%, rgba(124, 247, 198, 0.12), transparent 60%),
    var(--bg);
  color: var(--text);
  line-height: 1.6;
}

a {
  color: inherit;
  text-decoration: none;
}

a:hover {
  text-decoration: underline;
}

.container {
  width: min(100% - 32px, var(--max));
  margin-inline: auto;
}

.skip-link {
  position: absolute;
  left: -999px;
  top: 12px;
  background: var(--text);
  color: #000;
  padding: 10px 12px;
  border-radius: 10px;
  z-index: 1000;
}
.skip-link:focus {
  left: 12px;
}

.site-header {
  position: sticky;
  top: 0;
  z-index: 50;
  background: rgba(11, 18, 32, 0.7);
  backdrop-filter: blur(12px);
  border-bottom: 1px solid var(--line);
}

.header-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  padding: 14px 0;
  gap: 16px;
}

.brand {
  display: inline-flex;
  align-items: center;
  gap: 10px;
  font-weight: 700;
  letter-spacing: 0.2px;
}

.brand-mark {
  width: 36px;
  height: 36px;
  display: grid;
  place-items: center;
  border-radius: 12px;
  background: linear-gradient(135deg, rgba(76, 195, 255, 0.9), rgba(124, 247, 198, 0.9));
  color: #06101e;
  font-weight: 800;
}

.brand-name {
  font-size: 1.05rem;
}

.nav-toggle {
  display: none;
  border: 1px solid var(--line);
  background: rgba(255, 255, 255, 0.06);
  color: var(--text);
  border-radius: 12px;
  padding: 10px 12px;
  cursor: pointer;
}

.nav-list {
  display: flex;
  align-items: center;
  gap: 18px;
  list-style: none;
  padding: 0;
  margin: 0;
}

.btn {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  padding: 12px 16px;
  border-radius: 14px;
  background: linear-gradient(135deg, rgba(76, 195, 255, 0.95), rgba(124, 247, 198, 0.95));
  color: #06101e;
  font-weight: 700;
  border: 0;
  cursor: pointer;
  box-shadow: var(--shadow);
}

.btn:hover {
  text-decoration: none;
  transform: translateY(-1px);
}

.btn:active {
  transform: translateY(0);
}

.btn-small {
  padding: 10px 14px;
  border-radius: 12px;
}

.btn-ghost {
  background: rgba(255, 255, 255, 0.06);
  color: var(--text);
  border: 1px solid var(--line);
  box-shadow: none;
}

.btn-ghost:hover {
  transform: translateY(-1px);
}

.section {
  padding: 72px 0;
}

.section-alt {
  background: rgba(255, 255, 255, 0.03);
  border-top: 1px solid var(--line);
  border-bottom: 1px solid var(--line);
}

.section-header {
  max-width: 720px;
  margin-bottom: 28px;
}

.section-header h2 {
  margin: 0 0 10px;
  font-size: clamp(1.4rem, 2vw, 1.8rem);
}

.section-header p {
  margin: 0;
  color: var(--muted);
}

.hero {
  padding: 76px 0 34px;
}

.hero-grid {
  display: grid;
  grid-template-columns: 1.2fr 0.8fr;
  gap: 22px;
  align-items: start;
}

.eyebrow {
  margin: 0 0 10px;
  color: var(--muted);
}

.hero h1 {
  margin: 0 0 14px;
  font-size: clamp(2rem, 3vw, 2.7rem);
  line-height: 1.15;
}

.lead {
  margin: 0 0 20px;
  color: var(--muted);
  font-size: 1.05rem;
}

.hero-cta {
  display: flex;
  flex-wrap: wrap;
  gap: 12px;
  margin-bottom: 18px;
}

.trust-list {
  list-style: none;
  padding: 0;
  margin: 0;
  display: flex;
  flex-wrap: wrap;
  gap: 10px;
}

.trust-list li {
  border: 1px solid var(--line);
  background: rgba(255, 255, 255, 0.04);
  padding: 8px 10px;
  border-radius: 999px;
  color: var(--muted);
  font-size: 0.95rem;
}

.card {
  border: 1px solid var(--line);
  background: linear-gradient(180deg, rgba(255, 255, 255, 0.06), rgba(255, 255, 255, 0.03));
  border-radius: var(--radius);
  padding: 18px;
  box-shadow: var(--shadow);
}

.hero-card .card-title {
  margin: 0 0 12px;
  font-size: 1.1rem;
}

.card-note {
  margin: 12px 0 0;
  color: var(--muted);
  font-size: 0.95rem;
}

.grid {
  display: grid;
  gap: 14px;
}

.cards {
  grid-template-columns: repeat(3, 1fr);
}

.pricing {
  grid-template-columns: repeat(3, 1fr);
}

.team {
  grid-template-columns: repeat(4, 1fr);
}

.contact {
  grid-template-columns: 1.1fr 0.9fr;
  gap: 18px;
}

.card h3 {
  margin: 0 0 8px;
  font-size: 1.1rem;
}

.card p {
  margin: 0 0 10px;
  color: var(--muted);
}

.card p:last-child {
  margin-bottom: 0;
}

.checklist,
.bullet,
.info-list {
  margin: 0;
  padding-left: 18px;
  color: var(--muted);
}

.checklist li,
.bullet li,
.info-list li {
  margin: 6px 0;
}

.price-hint {
  margin-top: 0;
}

.highlight {
  border-color: rgba(76, 195, 255, 0.45);
  background: linear-gradient(180deg, rgba(76, 195, 255, 0.12), rgba(255, 255, 255, 0.03));
}

.note {
  margin-top: 14px;
  border: 1px solid var(--line);
  border-radius: var(--radius);
  padding: 14px;
  color: var(--muted);
  background: rgba(255, 255, 255, 0.03);
}

.steps {
  margin: 0;
  padding-left: 18px;
  display: grid;
  gap: 10px;
}

.steps h3 {
  margin: 0 0 4px;
  font-size: 1.05rem;
}

.steps p {
  margin: 0;
  color: var(--muted);
}

.person .role {
  margin: 0 0 8px;
  color: var(--text);
  opacity: 0.85;
  font-weight: 600;
}

.form .field {
  display: grid;
  gap: 6px;
  margin-bottom: 12px;
}

label {
  font-weight: 600;
}

input,
textarea {
  width: 100%;
  border-radius: 12px;
  border: 1px solid var(--line);
  background: rgba(0, 0, 0, 0.2);
  color: var(--text);
  padding: 10px 12px;
  font: inherit;
}

input:focus,
textarea:focus {
  outline: 2px solid rgba(76, 195, 255, 0.55);
  outline-offset: 2px;
}

.error {
  min-height: 18px;
  color: #ffd1d1;
  opacity: 0.9;
}

.form-note {
  margin: 10px 0 0;
  color: var(--muted);
  font-size: 0.95rem;
}

.info-list {
  list-style: none;
  padding-left: 0;
}

.info-list li {
  display: flex;
  gap: 10px;
  padding: 8px 0;
  border-bottom: 1px solid var(--line);
}

.info-list li:last-child {
  border-bottom: 0;
}

.info-list span {
  width: 92px;
  color: var(--text);
  opacity: 0.9;
  font-weight: 600;
}

.mini-faq {
  margin-top: 16px;
}

details {
  border: 1px solid var(--line);
  border-radius: 12px;
  padding: 10px 12px;
  background: rgba(255, 255, 255, 0.03);
  margin-top: 10px;
}

summary {
  cursor: pointer;
  font-weight: 700;
}

.site-footer {
  padding: 26px 0;
  border-top: 1px solid var(--line);
}

.footer-inner {
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 12px;
  flex-wrap: wrap;
  color: var(--muted);
}

.footer-links {
  display: flex;
  gap: 14px;
}

@media (max-width: 980px) {
  .hero-grid {
    grid-template-columns: 1fr;
  }
  .cards {
    grid-template-columns: 1fr;
  }
  .pricing {
    grid-template-columns: 1fr;
  }
  .team {
    grid-template-columns: 1fr 1fr;
  }
  .contact {
    grid-template-columns: 1fr;
  }
  .nav-toggle {
    display: inline-flex;
  }
  .nav-list {
    display: none;
    position: absolute;
    right: 16px;
    top: 62px;
    flex-direction: column;
    align-items: stretch;
    gap: 10px;
    padding: 12px;
    background: rgba(11, 18, 32, 0.95);
    border: 1px solid var(--line);
    border-radius: 16px;
    width: min(260px, calc(100vw - 32px));
  }
  .nav-list.is-open {
    display: flex;
  }
  .header-inner {
    position: relative;
  }
}

@media (prefers-reduced-motion: reduce) {
  html {
    scroll-behavior: auto;
  }
  .btn:hover {
    transform: none;
  }
}
function setYear() {
  const yearEl = document.getElementById("year");
  if (yearEl) yearEl.textContent = new Date().getFullYear();
}

function setupMobileMenu() {
  const toggle = document.querySelector("[data-nav-toggle]");
  const menu = document.querySelector("[data-nav-menu]");
  if (!toggle || !menu) return;

  toggle.addEventListener("click", () => {
    const isOpen = menu.classList.toggle("is-open");
    toggle.setAttribute("aria-expanded", String(isOpen));
  });

  menu.addEventListener("click", (e) => {
    const target = e.target;
    if (target && target.tagName === "A") {
      menu.classList.remove("is-open");
      toggle.setAttribute("aria-expanded", "false");
    }
  });
}

function validateEmail(value) {
  return /^[^\s@]+@[^\s@]+\.[^\s@]+$/.test(value);
}

function setupContactForm() {
  const form = document.getElementById("contactForm");
  const note = document.getElementById("formNote");
  if (!form || !note) return;

  function setError(fieldName, message) {
    const el = document.querySelector(`[data-error-for="${fieldName}"]`);
    if (el) el.textContent = message || "";
  }

  form.addEventListener("submit", (e) => {
    e.preventDefault();

    const name = form.elements.namedItem("name").value.trim();
    const email = form.elements.namedItem("email").value.trim();
    const company = form.elements.namedItem("company").value.trim();
    const message = form.elements.namedItem("message").value.trim();

    let ok = true;

    setError("name", "");
    setError("email", "");
    setError("message", "");
    note.textContent = "";

    if (!name) {
      setError("name", "Skriv inn navn.");
      ok = false;
    }
    if (!email || !validateEmail(email)) {
      setError("email", "Skriv inn en gyldig e post.");
      ok = false;
    }
    if (!message) {
      setError("message", "Skriv en kort melding om hva du trenger.");
      ok = false;
    }

    if (!ok) return;

    const subject = encodeURIComponent("Forespørsel fra nettsiden");
    const bodyLines = [
      `Navn: ${name}`,
      `E post: ${email}`,
      `Bedrift: ${company || "Ikke oppgitt"}`,
      "",
      "Melding:",
      message
    ];
    const body = encodeURIComponent(bodyLines.join("\n"));

    const to = "kontakt@nordintel.no";
    window.location.href = `mailto:${to}?subject=${subject}&body=${body}`;

    note.textContent = "E posten åpnes nå. Hvis ingenting skjer, kan du sende direkte til kontakt@nordintel.no.";
    form.reset();
  });
}

setYear();
setupMobileMenu();
setupContactForm();
# Nordintel nettside (statisk)

Dette er en enkel, rask og mobilvennlig nettside for Nordintel som kan hostes på GitHub Pages.

## Kom i gang
1. Last ned repoet eller klon det
2. Åpne `index.html` i nettleser for å teste lokalt

## Publiser på GitHub Pages
1. Gå til repo på GitHub
2. Settings
3. Pages
4. Source: Deploy from a branch
5. Branch: main, folder: / (root)
6. Lagre

Nettsiden blir tilgjengelig på GitHub Pages linken som GitHub viser.

## Tilpass
Bytt ut:
- E post og telefon i kontaktseksjonen
- Tekst, tjenester og eventuelle bilder (hvis dere legger til senere)

## Teknologi
- HTML, CSS, JavaScript
- Ingen framework, så det er lett å forstå og redigere
