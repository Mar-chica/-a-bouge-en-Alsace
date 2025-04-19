<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Découvrons l'Alsace</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background-color: #f2f2f2;
      color: #333;
    }
    header {
      background-color: #d71920;
      color: white;
      padding: 40px 20px;
      text-align: center;
    }
    header h1 {
      margin: 0;
      font-size: 2.5em;
    }
    header p {
      font-size: 1.2em;
    }
    .container {
      padding: 20px;
      max-width: 1000px;
      margin: auto;
    }
    img.hero {
      width: 100%;
      max-height: 400px;
      object-fit: cover;
      border-radius: 10px;
      margin-bottom: 20px;
    }
    section {
      margin-bottom: 40px;
    }
    section h2 {
      color: #d71920;
    }
    footer {
      background-color: #333;
      color: white;
      text-align: center;
      padding: 15px 10px;
    }

    /* Carrusel */
    .carousel {
      display: flex;
      overflow-x: auto;
      gap: 10px;
      scroll-snap-type: x mandatory;
    }
    .carousel img {
      scroll-snap-align: start;
      width: 300px;
      height: 200px;
      border-radius: 8px;
      object-fit: cover;
    }

    /* Formulario */
    form {
      display: flex;
      flex-direction: column;
      gap: 10px;
    }
    input, textarea {
      padding: 10px;
      border: 1px solid #ccc;
      border-radius: 5px;
      font-size: 1em;
    }
    button {
      background-color: #d71920;
      color: white;
      padding: 10px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
    }

    iframe {
      width: 100%;
      height: 300px;
      border: 0;
      border-radius: 10px;
    }

    @media (max-width: 600px) {
      header h1 {
        font-size: 1.8em;
      }
      .carousel img {
        width: 250px;
      }
    }
  </style>
</head>
<body>

  <header>
    <h1>Découvrons l'Alsace</h1>
    <p>Une région pleine de charme, de culture et de traditions</p>
  </header>

  <div class="container">
    <img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a2/Colmar_vue_depuis_l%27avion.jpg/1200px-Colmar_vue_depuis_l%27avion.jpg" alt="Vue d'Alsace" class="hero">

    <section>
      <h2>🌍 Où se trouve l'Alsace ?</h2>
      <p>L'Alsace est une région située à l'est de la France, proche de l'Allemagne et de la Suisse. Elle est connue pour ses villages pittoresques, ses maisons à colombages et ses marchés de Noël.</p>
    </section>

    <section>
      <h2>📸 Images de l'Alsace</h2>
      <div class="carousel">
        <img src="https://upload.wikimedia.org/wikipedia/commons/3/3a/Strasbourg_Cathedrale_Notre-Dame.jpg" alt="Strasbourg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/1/13/Kaysersberg_Alsace.jpg" alt="Kaysersberg">
        <img src="https://upload.wikimedia.org/wikipedia/commons/b/b0/Colmar_Quai_Poissonnerie.jpg" alt="Colmar">
        <img src="https://upload.wikimedia.org/wikipedia/commons/f/f4/Haut-Koenigsbourg_Castle.jpg" alt="Château">
      </div>
    </section>

    <section>
      <h2>🗺️ Carte interactive</h2>
      <iframe src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d2660379.250705298!2d5.343714145797504!3d47.71798478399309!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x4791654e1ab99167%3A0x40a5fb99a3cb560!2sAlsace!5e0!3m2!1sfr!2sfr!4v1713521210504!5m2!1sfr!2sfr" allowfullscreen="" loading="lazy" referrerpolicy="no-referrer-when-downgrade"></iframe>
    </section>

    <section>
      <h2>📩 Contact</h2>
      <form>
        <input type="text" placeholder="Votre nom" required>
        <input type="email" placeholder="Votre adresse e-mail" required>
        <textarea rows="4" placeholder="Votre message..."></textarea>
        <button type="submit">Envoyer</button>
      </form>
    </section>
  </div>

  <footer>
    <p>© 2025 Découvrons l'Alsace — Projet éducatif</p>
  </footer>

</body>
</html>

