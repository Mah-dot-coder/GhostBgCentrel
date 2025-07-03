<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>GhostBGCentral</title>
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background-color: #0d0d0d;
      color: #f5f5f5;
    }header {
  background: linear-gradient(90deg, #ff004f, #0ff);
  padding: 1rem 2rem;
  display: flex;
  justify-content: space-between;
  align-items: center;
  position: sticky;
  top: 0;
  z-index: 10;
}

.logo {
  font-size: 1.8rem;
  font-weight: bold;
  color: #fff;
  text-shadow: 0 0 10px #ff004f;
}

nav a {
  color: white;
  margin-left: 20px;
  text-decoration: none;
  font-weight: bold;
  transition: 0.3s;
}

nav a:hover {
  color: #0ff;
  text-shadow: 0 0 10px #0ff;
}

.hero {
  padding: 100px 20px;
  text-align: center;
}

.hero h1 {
  font-size: 3rem;
  color: #ff004f;
  text-shadow: 0 0 10px #ff004f;
}

.hero p {
  font-size: 1.2rem;
  margin-top: 1rem;
}

.section {
  padding: 60px 20px;
  max-width: 1000px;
  margin: auto;
}

.section h2 {
  color: #0ff;
  text-shadow: 0 0 8px #0ff;
  margin-bottom: 1rem;
}

footer {
  background: #111;
  padding: 20px;
  text-align: center;
  font-size: 0.9rem;
  border-top: 1px solid #333;
}

@media screen and (max-width: 600px) {
  header {
    flex-direction: column;
  }
  nav {
    margin-top: 10px;
  }
}

  </style>
</head>
<body>
  <header>
    <div class="logo">GhostBGCentral</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#videos">Videos</a>
      <a href="#blog">Blog</a>
      <a href="#about">About</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>  <section class="hero" id="home">
    <h1>Welcome to GhostBGCentral</h1>
    <p>Your place for tech, edits, mystery and more.</p>
  </section>  <section class="section" id="videos">
    <h2>Latest Videos</h2>
    <p>[Embed your YouTube videos here]</p>
  </section>  <section class="section" id="blog">
    <h2>Blog Posts</h2>
    <p>Coming soon: Ghost stories, tech rants, and more...</p>
  </section>  <section class="section" id="about">
    <h2>About Me</h2>
    <p>I’m Ghost BG, a creator who mixes tech, mystery, edits, and raw vibes. Stay tuned.</p>
  </section>  <section class="section" id="contact">
    <h2>Contact</h2>
    <p>Follow me on social: [Links here]</p>
  </section>  <footer>
    &copy; 2025 GhostBGCentral. All rights reserved.
  </footer>
</body>
</html>
