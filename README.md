<!DOCTYPE html>
<html lang="it">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Geometra Rossi</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      color: #333;
      background-color: #f9f9f9;
    }
    header {
      background-color: #003366;
      color: #fff;
      padding: 2rem;
      text-align: center;
    }
    nav {
      background: #0055aa;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: #fff;
      margin: 0 1rem;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #003366;
      margin-bottom: 1rem;
    }
    .gallery {
      display: flex;
      flex-wrap: wrap;
      gap: 1rem;
    }
    .item {
      flex: 1 1 200px;
      text-align: center;
    }
    .item img {
      max-width: 100%;
      border-radius: 4px;
    }
    form {
      display: flex;
      flex-direction: column;
      max-width: 500px;
      margin: auto;
    }
    form input, form textarea {
      padding: 0.5rem;
      margin-top: 0.5rem;
      margin-bottom: 1rem;
      border: 1px solid #ccc;
      border-radius: 4px;
    }
    form button {
      background-color: #003366;
      color: white;
      border: none;
      padding: 0.7rem;
      border-radius: 4px;
      cursor: pointer;
    }
    footer {
      background-color: #003366;
      color: white;
      text-align: center;
      padding: 1rem;
      margin-top: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Geometra Rossi</h1>
    <p>Topografia, BIM, pratiche edilizie e certificazioni energetiche</p>
  </header>

  <nav>
    <a href="#chi">Chi sono</a>
    <a href="#portfolio">Portfolio</a>
    <a href="#contatti">Contatti</a>
  </nav>

  <section id="chi">
    <h2>Chi sono</h2>
    <p>Geometra laureato con esperienza in topografia e geomatica. Collaboro con studi tecnici, utilizzo tecnologie avanzate come drone DJI Matrice 4T, BLK2GO, GNSS e SLAM. Offro servizi di rilievi, modellazione BIM, SCIA e certificazioni energetiche. Opero a Bologna e in tutta Italia.</p>
  </section>

  <section id="portfolio">
    <h2>Portfolio</h2>
    <div class="gallery">
      <div class="item">
        <img src="https://i.imgur.com/O0C6hhe.jpg" alt="BLK2GO">
        <p>BLK2GO - Rilievi interni 3D</p>
      </div>
      <div class="item">
        <img src="https://i.imgur.com/NR6eC2o.jpg" alt="Drone DJI Matrice 4T">
        <p>Drone DJI Matrice 4T - Rilievi aerei</p>
      </div>
      <div class="item">
        <img src="https://i.imgur.com/9zh2EjC.jpg" alt="Nuvola di punti">
        <p>Nuvola di punti - Modellazione BIM</p>
      </div>
      <div class="item">
        <img src="https://i.imgur.com/rmpUUlK.jpg" alt="Disegno tecnico">
        <p>Disegni di piante edilizie</p>
      </div>
      <div class="item">
        <img src="https://i.imgur.com/LNBf1XP.jpg" alt="Certificazione energetica">
        <p>Certificazioni energetiche APE</p>
      </div>
    </div>
    <p><a href="cv.pdf" download>Scarica il mio CV in PDF</a></p>
  </section>

  <section id="contatti">
    <h2>Contattami</h2>
    <form action="https://formspree.io/f/mwkgygqv" method="POST">
      <input type="text" name="nome" placeholder="Il tuo nome" required>
      <input type="email" name="email" placeholder="La tua email" required>
      <textarea name="messaggio" rows="5" placeholder="Scrivi il tuo messaggio..." required></textarea>
      <button type="submit">Invia</button>
    </form>
    <p>Email: <a href="mailto:geometra.rossi@email.com">geometra.rossi@email.com</a></p>
    <p>LinkedIn: <a href="#">linkedin.com/in/geometra-rossi</a></p>
  </section>

  <footer>
    &copy; 2025 Geometra Rossi. Tutti i diritti riservati.
  </footer>

</body>
</html>
