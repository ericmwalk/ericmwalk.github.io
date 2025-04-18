<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Eric Walker's Projects</title>
  <style>
    body {
      font-family: "Segoe UI", Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #1e1e2f;
      color: #f2f2f2;
      display: flex;
      flex-direction: column;
      align-items: center;
      min-height: 100vh;
    }
    header {
      background-color: #292942;
      width: 100%;
      padding: 1rem;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2rem;
    }
    main {
      padding: 2rem;
      max-width: 800px;
      width: 100%;
    }
    .project {
      margin-bottom: 2rem;
      padding: 1rem;
      background-color: #33334d;
      border-left: 4px solid #5dcef3;
      border-radius: 6px;
    }
    .project h2 {
      margin-top: 0;
      font-size: 1.5rem;
    }
    .project a {
      color: #5dcef3;
      text-decoration: none;
    }
    footer {
      margin-top: auto;
      padding: 1rem;
      text-align: center;
      font-size: 0.9rem;
      background-color: #292942;
      width: 100%;
    }
  </style>
</head>
<body>
  <header>
    <h1>👋 Hi, I'm Eric Walker</h1>
    <p>Welcome to my project hub! ⚙️</p>
  </header>
  <main>
    <div class="project">
      <h2>🪄 Lantern</h2>
      <p>A plugin for posting reviews from Obsidian to Micro.blog, with smart alt-text for images and more.</p>
      <a href="https://github.com/ericmwalk/obsidian-microblog" target="_blank">View on GitHub →</a>
    </div>
    <div class="project">
      <h2>⏳ Cruise Countdown</h2>
      <p>A themed countdown timer with rotating daily quips for an upcoming family cruise adventure.</p>
      <a href="https://gottfamily.fun" target="_blank">Visit Site →</a>
    </div>
    <div class="project">
      <h2>📚 Book Search + Reviews</h2>
      <p>A search tool using the Google Books API to find books, fetch metadata, and format reviews for Micro.blog.</p>
      <a href="https://github.com/ericmwalk/lantern" target="_blank">View on GitHub →</a>
    </div>
  </main>
  <footer>
    © <span id="year"></span> Eric Walker — <a href="https://github.com/ericmwalk" style="color:#5dcef3">GitHub Profile</a>
  </footer>
  <script>
    document.getElementById("year").textContent = new Date().getFullYear();
  </script>
</body>
</html>

