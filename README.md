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
