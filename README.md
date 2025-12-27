<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Biplob Kumardas — Writing</title>
  <link rel="stylesheet" href="styles.css" />
  </head>
<body>
  <!-- Top bar -->
  <header class="topbar">
    <a class="logo" href="/">Biplob Kumar Das</a>

    <nav class="nav">
      <a href="#featured">Featured</a>
      <a href="#latest">Latest</a>
      <a href="#topics">Topics</a>
      <a href="/about.html">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main class="wrap">
    <!-- Above-the-fold: two columns like a magazine homepage -->
    <section class="front">
      <!-- Left: big feature -->
      <article class="hero" id="featured">
        <a class="hero-link" href="articles/first-piece.html">
          <img class="hero-img" src="assets/img/hero.jpg" alt="Featured story image">
          <div class="hero-text">
            <p class="kicker">FEATURE</p>
            <h1 class="hero-title">Exclusive: India’s largest far-right Hindu organization hires U.S. lobbyists for congressional influence campaign</h1>
            <p class="deck">
              Squire Patton Boggs lobbied U.S. lawmakers on behalf of the Rashtriya Swayamsevak Sangh, a Hindu nationalist group linked to discrimination and violence against Muslims, a Prism investigation found
            </p>
            <p class="byline">By Meghnad Bose and Biplob Kumar Das • Prism / 2025</p>
          </div>
        </a>
      </article>

      <!-- Right: trending / picks list -->
      <aside class="rail">
        <h2 class="rail-title">Today’s Picks</h2>

        <a class="rail-item" href="articles/second-piece.html">
          <p class="kicker">ESSAY</p>
          <p class="rail-headline">Short headline for another strong piece</p>
          <p class="rail-meta">Publication • 2025</p>
        </a>

        <a class="rail-item" href="articles/third-piece.html">
          <p class="kicker">REPORTING</p>
          <p class="rail-headline">Another headline that fits on 1–2 lines</p>
          <p class="rail-meta">Publication • 2024</p>
        </a>

        <a class="rail-item" href="articles/fourth-piece.html">
          <p class="kicker">INTERVIEW</p>
          <p class="rail-headline">One more headline</p>
          <p class="rail-meta">Publication • 2023</p>
        </a>
      </aside>
    </section>

    <!-- Grid of story cards -->
    <section class="section" id="latest">
      <div class="section-head">
        <h2>Latest</h2>
        <a class="smalllink" href="/archive.html">View all</a>
      </div>

      <div class="grid">
        <article class="card">
          <a href="articles/second-piece.html">
            <img class="thumb" src="assets/img/thumb1.jpg" alt="">
            <p class="kicker">CULTURE</p>
            <h3 class="card-title">Title of the piece</h3>
            <p class="card-deck">One sentence about what the reader gets.</p>
            <p class="card-meta">Publication • 2025</p>
          </a>
        </article>

        <article class="card">
          <a href="articles/third-piece.html">
            <div class="thumb placeholder" aria-hidden="true"></div>
            <p class="kicker">TECH</p>
            <h3 class="card-title">Title of the piece</h3>
            <p class="card-deck">One sentence about what the reader gets.</p>
            <p class="card-meta">Publication • 2025</p>
          </a>
        </article>

        <article class="card">
          <a href="articles/fourth-piece.html">
            <div class="thumb placeholder" aria-hidden="true"></div>
            <p class="kicker">OPINION</p>
            <h3 class="card-title">Title of the piece</h3>
            <p class="card-deck">One sentence about what the reader gets.</p>
            <p class="card-meta">Publication • 2024</p>
          </a>
        </article>
      </div>
    </section>

    <!-- Topic blocks -->
    <section class="section" id="topics">
      <div class="section-head">
        <h2>Topics</h2>
      </div>

      <div class="topics">
        <a class="topic" href="/topic/tech.html">Tech</a>
        <a class="topic" href="/topic/culture.html">Culture</a>
        <a class="topic" href="/topic/politics.html">Politics</a>
        <a class="topic" href="/topic/essays.html">Essays</a>
      </div>
    </section>

    <section class="section" id="contact">
      <div class="section-head">
        <h2>Contact</h2>
      </div>
      <p>Email: <a href="mailto:you@email.com">you@email.com</a></p>
      <p>
        <a href="https://twitter.com/yourhandle">X/Twitter</a> •
        <a href="https://www.linkedin.com/in/yourname/">LinkedIn</a> •
        <a href="https://medium.com/@you">Medium</a>
      </p>
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
