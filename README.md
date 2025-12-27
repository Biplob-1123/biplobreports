<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Biplob Kumar Das — Writing</title>
  <meta name="description" content="Portfolio of reporting and writing by Biplob Kumar Das." />
  <link rel="stylesheet" href="styles.css" />
</head>

<body>
  <!-- Top bar -->
  <header class="topbar">
    <a class="logo" href="/">Biplob Kumar DasE</a>

    <nav class="nav">
      <a href="#work">Work</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="wrap">
    <!-- Minimal hero -->
    <section class="hero">
      <p class="kicker">REPORTER</p>
      <h1 class="title">Biplob Kumar Das</h1>
      <p class="deck">
        “I report on politics, businesses and immigrant communities.”
      </p>

      <div class="links">
        <a href="mailto:biplobkumardas@protonmail.com">biplobkumardas@protonmail.com</a>
        <span class="dot">•</span>
        <a href="https://github.com/yourusername" target="_blank" rel="noopener">GitHub</a>
        <span class="dot">•</span>
        <a href="https://www.linkedin.com/in/BiplobKumarDas/" target="_blank" rel="noopener">LinkedIn</a>
      </div>
    </section>

    <!-- Articles grid (simple, no categories) -->
    <section id="work" class="work">
      <div class="grid">
        <!-- 1 -->
        <article class="card">
          <a href="https://prismreports.org/2025/11/12/rss-squire-patton-boggs-lobbying-congress/" target="_blank" rel="noopener">
            <p class="pub">Prism</p>
            <h2 class="headline">Exclusive: India’s largest far-right Hindu organization hires U.S. lobbyists for congressional influence campaign</h2>
            <p class="meta">Nov 12, 2025</p>
          </a>
        </article>

        <!-- 2 -->
        <article class="card">
          <a href="https://documentedny.com/2025/11/04/halal-food-trucks-back-mamdani/" target="_blank" rel="noopener">
            <p class="pub">Documented</p>
            <h2 class="headline">Zohran Mamdani to Street Vendors: I’m Listening</h2>
            <p class="meta">Nov 4, 2025</p>
          </a>
        </article>

        <!-- 3 -->
        <article class="card">
          <a href="https://documentedny.com/2025/10/27/cuomo-muslim-south-asian-islamophobic/" target="_blank" rel="noopener">
            <p class="pub">Documented</p>
            <h2 class="headline">Cuomo’s Outreach to South Asians Shadowed by Far-Right Anti-Muslim Ties</h2>
            <p class="meta">Oct 27, 2025</p>
          </a>
        </article>

        <!-- 4 -->
        <article class="card">
          <a href="https://documentedny.com/2025/09/04/desi-storeowners-queens-trumps-tariffs-india/" target="_blank" rel="noopener">
            <p class="pub">Documented</p>
            <h2 class="headline">South Asian Storeowners ‘Doomed’ by Trump’s 50% Tariffs on India Imports</h2>
            <p class="meta">Sep 4, 2025</p>
          </a>
        </article>

        <!-- 5 -->
        <article class="card">
          <a href="https://www.dropsitenews.com/p/modi-epstein-files-steve-bannon-india-trump-bjp" target="_blank" rel="noopener">
            <p class="pub">DropSite News</p>
            <h2 class="headline">“Modi on board”: Jeffrey Epstein Pressed Steve Bannon to Meet With Indian PM Shortly Before His Death</h2>
            <p class="meta">DropSite News</p>
          </a>
        </article>

        <!-- 6 -->
        <article class="card">
          <a href="https://www.dropsitenews.com/p/campaign-spending-mamdani-cuomo-billionaires-bill-ackman-new-york-city-mayoral-race" target="_blank" rel="noopener">
            <p class="pub">DropSite News</p>
            <h2 class="headline">The Money Versus Mamdani in the Final Stretch of NYC Mayoral Race</h2>
            <p class="meta">DropSite News</p>
          </a>
        </article>

        <!-- 7 -->
        <article class="card">
          <a href="https://www.newindiaabroad.com/english/news/proud-of-my-hindu-heritage-mamdani-visits-nyc-temples-to-connect-with-supporters" target="_blank" rel="noopener">
            <p class="pub">New India Abroad</p>
            <h2 class="headline">“Proud of my Hindu Heritage”: Mamdani visits NYC temples to connect with supporters</h2>
            <p class="meta">New India Abroad</p>
          </a>
        </article>

        <!-- 8 -->
        <article class="card">
          <a href="https://www.newindiaabroad.com/english/indian-diaspora-community/hindus-for-zohran-organizes-prayer-meet-for-mamdani-in-ny" target="_blank" rel="noopener">
            <p class="pub">New India Abroad</p>
            <h2 class="headline">Hindus For Zohran organizes prayer meet for Mamdani in NY</h2>
            <p class="meta">New India Abroad</p>
          </a>
        </article>
      </div>
    </section>

    <!-- About + Contact (simple) -->
    <section id="about" class="simple">
      <h2>About</h2>
      <p>
        I am an independent journalist based in New York City. I previously worked as a business correspondent for Reuters. In 2025, I graduated from the Columbia Journalism School with a Master's in Journalism. I report on stories at the intersection of politics and business with an investigative lens.
      </p>
    </section>

    <section id="contact" class="simple">
      <h2>Contact</h2>
      <p>Email: <a href="mailto:biplobkumardas@protonmail.com">biplobkumardas@protonmail.com</a></p>
    </section>
  </main>

  <footer class="footer">
    <p>© <span id="y"></span> Biplob Kumar Das</p>
  </footer>

  <script>
    document.getElementById("y").textContent = new Date().getFullYear();
  </script>
</body>
</html>
