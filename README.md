# seforim
free seforim online free texts and shiurim
seforim-site/
├── index.html        <-- Main homepage
├── css/              
│   └── styles.css    <-- CSS file for styling
└── images/           <-- Optional: Folder for images (add images if needed)

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Seforim Collection</title>
  <link rel="stylesheet" href="css/styles.css" />
</head>
<body>
  <header>
    <h1>Seforim Collection</h1>
  </header>

  <main>
    <section>
      <h2>🎧 Free Audio</h2>
      <p>
        Dive into a world of <strong>Shiurim, Niggunim, and More</strong>! Our team collected content from various sources containing thousands of shiurim, niggunim, etc.
      </p>
      <a href="[https://drive.google.com/drive/folders/your-audio-folder-id](https://docs.google.com/spreadsheets/d/1G0PBTvkHQx9ahY9OKZtcOaVfCHNFwKXGSM1hpNH6Ja8/edit?gid=1732301421#gid=1732301421)" target="_blank" class="button">Access the Audio Collection</a>
    </section>

    <section>
      <h2>📚 Texts and Documents</h2>
      <p>
        Enjoy this collection of texts. Please note that some files may not have been acquired with full permission. Contact your Rav before using them for any halachic or public purposes.
      </p>
      <a href="[https://drive.google.com/drive/folders/your-texts-folder-id](https://docs.google.com/spreadsheets/d/1Et_oE7ZYPSM0SC4qFY-_XGDZHwcVT-xDht05Ak4_TnA/edit?gid=215597516#gid=215597516)" target="_blank" class="button">View Texts and Docs</a>
    </section>

    <section>
      <h2>📬 Contact</h2>
      <p>Email: <a href="mailto:heshyedelkopf@gmail.com">heshyedelkopf@gmail.com</a></p>
      <p>Location: Crown Heights, Brooklyn, NY</p>
    </section>
  </main>

  <footer>
    <p>© 2025 by H. H. Edelkopf. Originally hosted on Wix.</p>
  </footer>
</body>
</html>
body {
  font-family: 'Segoe UI', sans-serif;
  margin: 0;
  padding: 0;
  background: #fefefe;
  color: #333;
}

header, footer {
  background-color: #1e3a8a;
  color: white;
  text-align: center;
  padding: 1em 0;
}

main {
  padding: 2em;
  max-width: 800px;
  margin: auto;
}

section {
  margin-bottom: 2em;
  padding: 1em;
  border: 1px solid #ccc;
  border-radius: 10px;
  background-color: #f9f9f9;
}

h1, h2 {
  color: #1e3a8a;
}

.button {
  display: inline-block;
  padding: 0.6em 1.2em;
  margin-top: 0.5em;
  background-color: #2563eb;
  color: white;
  text-decoration: none;
  border-radius: 8px;
  transition: background-color 0.3s ease;
}

.button:hover {
  background-color: #1d4ed8;
}

a {
  color: #2563eb;
}
