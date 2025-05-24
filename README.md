<!DOCTYPE html>
<html lang="id">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1" />
<title>Website Teman Saya</title>
<style>
  @import url('https://fonts.googleapis.com/css2?family=Poppins:wght@300;600&display=swap');

  body {
    margin: 0;
    font-family: 'Poppins', sans-serif;
    background: linear-gradient(135deg, #ff416c 0%, #ff4b2b 100%);
    color: #fff;
    display: flex;
    flex-direction: column;
    min-height: 100vh;
    justify-content: center;
    align-items: center;
    padding: 2rem;
    text-align: center;
  }

  .container {
    background: rgba(255, 255, 255, 0.15);
    border-radius: 20px;
    padding: 3rem 3.5rem;
    max-width: 500px;
    box-shadow: 0 10px 40px rgba(0, 0, 0, 0.25);
  }

  h1 {
    font-size: 3rem;
    margin-bottom: 0.3rem;
    font-weight: 600;
    letter-spacing: 1.4px;
    text-shadow: 0 2px 8px rgba(0,0,0,0.4);
  }

  h2 {
    font-weight: 300;
    font-size: 1.2rem;
    margin-top: 0;
    margin-bottom: 1.8rem;
    opacity: 0.9;
    text-shadow: 0 2px 6px rgba(0,0,0,0.25);
  }

  p.about {
    font-size: 1.1rem;
    line-height: 1.6;
    margin-bottom: 2.5rem;
    opacity: 0.95;
  }

  .social-links {
    display: flex;
    justify-content: center;
    gap: 1.8rem;
  }

  .social-links a {
    color: #fff;
    font-weight: 600;
    font-size: 1.2rem;
    text-decoration: none;
    padding: 0.6rem 1.3rem;
    border: 2px solid transparent;
    border-radius: 35px;
    transition: all 0.35s ease;
    box-shadow: 0 3px 7px rgba(0,0,0,0.22);
    background: rgba(255,255,255,0.2);
    user-select: none;
  }

  .social-links a:hover, .social-links a:focus {
    background: #fff;
    color: #ff4b2b;
    font-weight: 700;
    border-color: #ff4b2b;
    outline: none;
  }

  footer {
    margin-top: 3.2rem;
    font-size: 0.95rem;
    opacity: 0.75;
  }
</style>
</head>
<body>
  <main class="container" role="main">
    <h1>Halo, Sahabat!</h1>
    <h2>Kami yang selalu ada untukmu</h2>
    <p class="about">Jangan nangis lagi ya MELITA.</p>
    <nav class="social-links" aria-label="Tautan media sosial dan kontak">
      <a href="https://instagram.com" target="_blank" rel="noopener noreferrer" aria-label="Instagram">Instagram</a>
      <a href="https://twitter.com" target="_blank" rel="noopener noreferrer" aria-label="Twitter">Twitter</a>
      <a href="mailto:teman@example.com" aria-label="Email Teman">Email</a>
    </nav>
  </main>
  <footer>&copy; Melita pasti bisa kok, SEMANGAT.</footer>
</body>
</html>

