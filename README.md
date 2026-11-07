# blackwood-empire
Blackwood Empire — Character Archive
<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Blackwood Empire | Character Archive</title>

<style>
@import url('https://fonts.googleapis.com/css2?family=Cormorant+Garamond:wght@400;500;600;700&family=Playfair+Display:wght@400;600;700&display=swap');

:root {
  --bg: #09090d;
  --panel: #14131a;
  --gold: #c9a66b;
  --cream: #e9dfd0;
  --muted: #99919f;
  --line: #302735;
}

* {
  box-sizing: border-box;
  margin: 0;
  padding: 0;
}

html {
  scroll-behavior: smooth;
}

body {
  background: var(--bg);
  color: var(--cream);
  font-family: 'Cormorant Garamond', serif;
  font-size: 18px;
}

a {
  color: inherit;
  text-decoration: none;
}

header {
  padding: 24px 7%;
  border-bottom: 1px solid var(--line);
  display: flex;
  align-items: center;
  justify-content: space-between;
  gap: 15px;
  flex-wrap: wrap;
}

.logo {
  font-family: 'Playfair Display', serif;
  font-size: 25px;
  color: var(--gold);
  letter-spacing: 2px;
}

nav {
  display: flex;
  gap: 22px;
  flex-wrap: wrap;
}

nav a {
  color: var(--muted);
  transition: .3s;
}

nav a:hover {
  color: var(--gold);
}

.hero {
  min-height: 450px;
  padding: 80px 7%;
  text-align: center;
  display: flex;
  flex-direction: column;
  justify-content: center;
  align-items: center;
  background:
    radial-gradient(ellipse at center, #352136 0%, #17121c 42%, #09090d 80%);
}

.eyebrow {
  color: var(--gold);
  letter-spacing: 5px;
  text-transform: uppercase;
  font-size: 14px;
}

.hero h1 {
  font-family: 'Playfair Display', serif;
  font-size: clamp(40px, 9vw, 78px);
  font-weight: 400;
  margin: 18px 0;
  line-height: 1.1;
}

.hero h1 span {
  color: var(--gold);
}

.hero p {
  max-width: 550px;
  color: var(--muted);
  font-size: 22px;
  line-height: 1.5;
}

.btn {
  margin-top: 30px;
  padding: 13px 28px;
  border: 1px solid var(--gold);
  color: var(--gold);
  display: inline-block;
  letter-spacing: 2px;
  text-transform: uppercase;
  font-size: 14px;
  transition: .3s;
}

.btn:hover {
  background: var(--gold);
  color: #09090d;
}

section {
  padding: 65px 7%;
}

.section-title {
  text-align: center;
  margin-bottom: 35px;
}

.section-title h2 {
  font-family: 'Playfair Display', serif;
  font-size: 35px;
  font-weight: 400;
  color: var(--gold);
}

.section-title p {
  color: var(--muted);
  margin-top: 8px;
}

.search {
  display: block;
  width: 100%;
  max-width: 500px;
  margin: 0 auto 30px;
  padding: 14px 18px;
  background: var(--panel);
  border: 1px solid var(--line);
  color: var(--cream);
  font-family: inherit;
  font-size: 18px;
  outline: none;
}

.search:focus {
  border-color: var(--gold);
}

.grid {
  display: grid;
  grid-template-columns: repeat(auto-fit, minmax(230px, 1fr));
  gap: 20px;
}

.card {
  background: var(--panel);
  border: 1px solid var(--line);
  padding: 30px 24px;
  text-align: center;
  transition: .3s;
}

.card:hover {
  transform: translateY(-5px);
  border-color: var(--gold);
}

.symbol {
  font-size: 42px;
  color: var(--gold);
  margin-bottom: 15px;
}

.card h3 {
  font-family: 'Playfair Display', serif;
  font-size: 25px;
  font-weight: 400;
}

.card .role {
  color: var(--gold);
  font-size: 14px;
  letter-spacing: 2px;
  text-transform: uppercase;
  margin: 10px 0;
}

.card p {
  color: var(--muted);
  line-height: 1.5;
}

.card a {
  display: inline-block;
  margin-top: 18px;
  color: var(--gold);
  border-bottom: 1px solid var(--gold);
}

.empty {
  display: none;
  text-align: center;
  color: var(--muted);
  padding: 30px;
}

.about {
  background: #100d14;
  text-align: center;
}

.about p {
  max-width: 650px;
  margin: 20px auto;
  color: var(--muted);
  font-size: 22px;
  line-height: 1.7;
}

footer {
  border-top: 1px solid var(--line);
  padding: 30px 7%;
  text-align: center;
  color: var(--muted);
}

footer span {
  color: var(--gold);
}

@media (max-width: 500px) {
  header {
    justify-content: center;
    text-align: center;
  }

  nav {
    justify-content: center;
    gap: 15px;
    font-size: 16px;
  }

  .hero {
    padding: 65px 6%;
  }

  section {
    padding: 50px 6%;
  }
}
</style>
</head>

<body>

<header>
  <a href="#" class="logo">✦ BLACKWOOD ✦</a>
  <nav>
    <a href="#home">Home</a>
    <a href="#archive">Characters</a>
    <a href="#about">About</a>
  </nav>
</header>

<main>

<section class="hero" id="home">
  <div class="eyebrow">A universe of forgotten stories</div>

  <h1>Welcome to the<br><span>Blackwood Empire</span></h1>

  <p>
    Every soul has a story. Every story has a secret.
    Enter a world of original characters, mysterious
    personalities, and beautiful fictional destinies.
  </p>

  <a href="#archive" class="btn">Enter the Archive ✦</a>
</section>

<section id="archive">
  <div class="section-title">
    <h2>Character Archive</h2>
    <p>Meet the souls of our fictional universe.</p>
  </div>

  <input
    type="search"
    class="search"
    id="search"
    placeholder="Search characters..."
    aria-label="Search characters"
  >

  <div class="grid" id="characters">

    <!-- CHARACTER 1 -->
    <article class="card">
      <div class="symbol">♛</div>
      <h3>Character One</h3>
      <div class="role">The Enigmatic King</div>
      <p>A mysterious soul wrapped in elegance,
      secrets, and an untold past.</p>
      <a href="characters/character-one.html">Read Story →</a>
    </article>

    <!-- CHARACTER 2 -->
    <article class="card">
      <div class="symbol">❀</div>
      <h3>Character Two</h3>
      <div class="role">The Rose of Midnight</div>
      <p>Beautiful, captivating, and hiding
      a thousand stories behind her smile.</p>
      <a href="characters/character-two.html">Read Story →</a>
    </article>

    <!-- CHARACTER 3 -->
    <article class="card">
      <div class="symbol">☾</div>
      <h3>Character Three</h3>
      <div class="role">The Silent Phantom</div>
      <p>A quiet presence whose secrets
      are deeper than the night.</p>
      <a href="characters/character-three.html">Read Story →</a>
    </article>

    <!-- CHARACTER 4 -->
    <article class="card">
      <div class="symbol">♜</div>
      <h3>Character Four</h3>
      <div class="role">The Fallen Noble</div>
      <p>Once surrounded by glory,
      now searching for redemption.</p>
      <a href="characters/character-four.html">Read Story →</a>
    </article>

  </div>

  <p class="empty" id="empty">No characters found.</p>
</section>

<section class="about" id="about">
  <div class="section-title">
    <h2>About the Empire</h2>
  </div>

  <p>
    Blackwood Empire is a personal fictional universe
    dedicated to original characters, storytelling,
    imagination, and creative worlds.
  </p>

  <p>
    Every character deserves a place to exist.
    Every story deserves to be remembered.
  </p>

  <div style="color:var(--gold);font-size:25px;margin-top:25px;">
    ✦ ❀ ✦
  </div>
</section>

</main>

<footer>
  <p>© 2026 <span>Blackwood Empire</span></p>
  <p>Created with love, imagination & a little darkness ♡</p>
</footer>

<script>
const search = document.getElementById("search");
const cards = document.querySelectorAll(".card");
const empty = document.getElementById("empty");

search.addEventListener("input", function() {
  const query = this.value.toLowerCase();
  let visible = 0;

  cards.forEach(card => {
    const match = card.textContent.toLowerCase().includes(query);
    card.style.display = match ? "" : "none";
    if (match) visible++;
  });

  empty.style.display = visible === 0 ? "block" : "none";
});
</script>

</body>
</html>
