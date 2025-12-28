# tongstevenlohs-ui.github.io
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Film & Culture Blog</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Merriweather:wght@300;400;700&family=Playfair+Display:wght@600;700&display=swap" rel="stylesheet">

  <style>
    body {
      margin: 0;
      font-family: 'Merriweather', serif;
      background-color: #f7f7f7;
      color: #222;
      line-height: 1.7;
    }

    /* Header */
    header {
      background: #000;
      color: #fff;
      padding: 30px 0;
      text-align: center;
    }

    header h1 {
      font-family: 'Playfair Display', serif;
      font-size: 2.8rem;
      margin: 0;
    }

    header p {
      margin-top: 8px;
      font-size: 1rem;
      color: #ccc;
    }

    /* Layout */
    .container {
      max-width: 1100px;
      margin: 40px auto;
      padding: 0 20px;
      display: grid;
      grid-template-columns: 3fr 1fr;
      gap: 40px;
    }

    /* Blog Post */
    article {
      background: #fff;
      padding: 30px;
      margin-bottom: 40px;
      border-left: 5px solid #000;
    }

    article h2 {
      font-family: 'Playfair Display', serif;
      font-size: 2rem;
      margin-top: 0;
    }

    .meta {
      font-size: 0.9rem;
      color: #777;
      margin-bottom: 20px;
    }

    article p {
      margin-bottom: 18px;
    }

    article a {
      color: #000;
      font-weight: bold;
      text-decoration: none;
    }

    article a:hover {
      text-decoration: underline;
    }

    /* Sidebar */
    aside {
      background: #fff;
      padding: 25px;
      height: fit-content;
    }

    aside h3 {
      font-family: 'Playfair Display', serif;
      margin-top: 0;
      border-bottom: 2px solid #000;
      padding-bottom: 8px;
    }

    aside ul {
      list-style: none;
      padding-left: 0;
    }

    aside li {
      margin-bottom: 12px;
    }

    aside a {
      text-decoration: none;
      color: #000;
    }

    aside a:hover {
      text-decoration: underline;
    }

    /* Footer */
    footer {
      text-align: center;
      padding: 30px;
      background: #000;
      color: #fff;
      margin-top: 60px;
    }

    /* Responsive */
    @media (max-width: 900px) {
      .container {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>

<body>

<header>
  <h1>Film & Culture</h1>
  <p>Reviews, essays, and reflections</p>
</header>

<main class="container">

  <!-- Main Content -->
  <section>

    <article>
      <h2>The Power of Quiet Storytelling</h2>
      <div class="meta">By Steven Tong • December 28, 2025</div>
      <p>
        Some films do not announce themselves loudly. They arrive softly, confident
        that attention will follow. These are the films that trust the audience.
      </p>
      <p>
        Quiet storytelling allows characters to breathe, scenes to linger, and
        emotions to grow naturally rather than being forced upon us.
      </p>
      <a href="#">Read full review →</a>
    </article>

    <article>
      <h2>Why We Keep Returning to the Classics</h2>
      <div class="meta">By Steven Tong • December 20, 2025</div>
      <p>
        The best films do not age; they deepen. Every viewing becomes a conversation
        between who we were and who we are now.
      </p>
      <a href="#">Read full essay →</a>
    </article>

  </section>

  <!-- Sidebar -->
  <aside>
    <h3>About</h3>
    <p>
      A blog dedicated to thoughtful film criticism, cultural commentary,
      and long-form writing.
    </p>

    <h3>Categories</h3>
    <ul>
      <li><a href="#">Film Reviews</a></li>
      <li><a href="#">Essays</a></li>
      <li><a href="#">Classic Cinema</a></li>
      <li><a href="#">Modern Film</a></li>
    </ul>
  </aside>

</main>

<footer>
  © 2025 Film & Culture • Inspired by classic criticism
</footer>

</body>
</html>
