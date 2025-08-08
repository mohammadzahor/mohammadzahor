import os
from openai import OpenAI

client = OpenAI(
    base_url="https://router.huggingface.co/v1",
    api_key=os.environ["HF_TOKEN"],
)

completion = client.chat.completions.create(
    model="moonshotai/Kimi-K2-Instruct",
    messages=[
        {
            "role": "user",
            "content": "nonprofit organization"
        }
    ],
)

print(completion.choices[0].message)## Hi there 👋

<!--
**mohammadzahor/mohammadzahor** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
<!DOCTYPE html><html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Mohammad Zahoor Noori - Web Developer</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f4f4f4;
      color: #333;
    }
    header {
      background: linear-gradient(to right, #0a3d62, #3c6382);
      color: white;
      padding: 60px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
    }
    section {
      max-width: 1000px;
      margin: 40px auto;
      padding: 20px;
      background: white;
      border-radius: 8px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }
    h2 {
      color: #0a3d62;
    }
    .contact {
      text-align: center;
    }
    .contact a {
      color: #0a3d62;
      text-decoration: none;
      font-weight: bold;
    }
    footer {
      text-align: center;
      padding: 20px;
      background-color: #0a3d62;
      color: white;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mohammad Zahoor Noori</h1>
    <p>Web Developer | US Army Ally | Founder of NooriZone</p>
  </header>  <section>
    <h2>About Me</h2>
    <p>I am Mohammad Zahoor Noori, a Kabul-based web developer and entrepreneur. From 2006 to 2017, I worked shoulder-to-shoulder with US Army patriots across Afghanistan, supporting mission-critical operations. Today, I use my 20+ years of experience to build technology solutions that empower communities, especially Afghan Americans.</p>
  </section>  <section>
    <h2>Developer Profile</h2>
    <p>I specialize in full-stack development, building responsive websites and scalable platforms. I'm the founder of NooriZone and an advocate of blockchain technologies for secure, accessible finance.</p>
    <ul>
      <li>Languages: HTML, CSS, JavaScript, Python</li>
      <li>Tools: React, Tailwind, Node.js, Git</li>
      <li>GitHub: <a href="https://github.com/mohammadzahor" target="_blank">github.com/mohammadzahor</a></li>
    </ul>
  </section>  <section>
    <h2>US Army Service</h2>
    <p>I proudly served alongside the United States Army as a prime contractor, providing engineering, logistics, and operations support in high-risk environments. My work contributed directly to the safety and success of American forces in Afghanistan.</p>
    <p>Vendor ID: 57913 | UEI: UQNBMY8X1CN3 | CAGE: SJT37</p>
  </section>  <section class="contact">
    <h2>Contact</h2>
    <p>Email: mohammadzahoor.linkdin.com</p>
    <p>LinkedIn: <a href="https://mohammadzahoor.linkdin.com" target="_blank">mohammadzahoor.linkdin.com</a></p>
  </section>  <footer>
    <p>&copy; 2025 Mohammad Zahoor Noori. All Rights Reserved.</p>
  </footer>
</body>
</html>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js?client=ca-pub-5058730484953261"
     crossorigin="anonymous"></script>
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Noori Movie App – CEO Mohammadzahor</title>
  <style>
    body {
      margin: 0;
      font-family: Arial, sans-serif;
      background-color: #f4f4f4;
      color: #333;
    }

    header {
      background-color: #000;
      color: #fff;
      padding: 20px 0;
      text-align: center;
    }

    header h1 {
      margin: 0;
      font-size: 2em;
    }

    .container {
      padding: 20px;
      max-width: 1100px;
      margin: auto;
    }

    section {
      margin-bottom: 40px;
    }

    .movies {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }

    .movie {
      background: white;
      padding: 15px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0,0,0,0.1);
    }

    .movie h3 {
      margin-top: 0;
    }

    footer {
      background-color: #222;
      color: #ccc;
      text-align: center;
      padding: 20px 0;
    }

    code {
      background-color: #eee;
      padding: 2px 5px;
      border-radius: 3px;
    }

    a {
      color: #0066cc;
      text-decoration: none;
    }
  </style>
</head>
<body>
  <header>
    <h1>CEO @Noori Groups – Mohammadzahor</h1>
    <p>Creator & Owner of the Dynamic Movie App</p>
  </header>

  <div class="container">

    <section>
      <h2>About the Movie App</h2>
      <p>
        Welcome to the official webpage for the Noori Movie App – developed and maintained by 
        <strong>Mohammadzahor</strong>, a visionary entrepreneur and tech leader behind <strong>Noori Groups</strong>. 
        This application brings the latest movies, live search, and real-time streaming capabilities 
        powered by dynamic APIs.
      </p>
    </section>

    <section>
      <h2>Live Movie Listings (Dynamic API Integration)</h2>
      <div class="movies" id="movieList">
        <!-- Movies will load here -->
      </div>
    </section>

    <section>
      <h2>Available APIs</h2>
      <ul>
        <li><code>GET /api/movies</code> - Fetch latest movies</li>
        <li><code>GET /api/movies/:id</code> - Get movie details</li>
        <li><code>POST /api/user/favorites</code> - Save user favorites</li>
        <li><code>GET /api/search?q=</code> - Search movies in real time</li>
      </ul>
    </section>

    <section>
      <h2>Contact</h2>
      <p>For partnerships, press, or tech collaboration, contact:</p>
      <p><strong>Email:</strong> <a href="mailto:zzcc.zahoor@gmail.com">zzcc.zahoor@gmail.com</a></p>
      <p><strong>GitHub:</strong> <a href="https://github.com/mohammadzahor" target="_blank">github.com/mohammadzahor</a></p>
    </section>

  </div>

  <footer>
    <p>&copy; 2025 Noori Groups. All rights reserved. Powered by Mohammadzahor.</p>
  </footer>

  <script>
    // Simulated API response
    const movies = [
      { title: "Afghan Legend", year: "2025", description: "A heroic tale of resilience.", id: 1 },
      { title: "Kabul Dreams", year: "2024", description: "Drama of hope and unity.", id: 2 },
      { title: "Code of Honor", year: "2023", description: "Inspired by real missions.", id: 3 }
    ];

    const movieList = document.getElementById('movieList');

    movies.forEach(movie => {
      const div = document.createElement('div');
      div.className = 'movie';
      div.innerHTML = `<h3>${movie.title} (${movie.year})</h3><p>${movie.description}</p>`;
      movieList.appendChild(div);
    });
  </script>
</body>
</html>