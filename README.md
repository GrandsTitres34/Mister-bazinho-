

<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Mister Bazinho - Services Informatiques et Marketing Digital</title>
  <style>
    /* Styles CSS de base */
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
    }
    header, main, footer {
      padding: 20px;
    }
    h1, h2, h3 {
      color: #333;
    }
    a {
      color: #007bff;
      text-decoration: none;
    }
    a:hover {
      text-decoration: underline;
    }
    
    /* Styles personnalisés */
    header {
      background-color: #0077b6;
      color: #fff;
      display: flex;
      justify-content: space-between;
      align-items: center;
    }
    nav ul {
      display: flex;
      justify-content: center;
      list-style-type: none;
      padding: 0;
    }
    nav li {
      margin: 0 20px;
    }
    nav a {
      color: #fff;
    }
    .hero {
      background-image: url('hero-image.jpg');
      background-size: cover;
      background-position: center;
      color: #fff;
      padding: 100px 20px;
      text-align: center;
    }
    .hero h1 {
      font-size: 48px;
      margin-bottom: 20px;
    }
    .hero p {
      font-size: 24px;
      margin-bottom: 40px;
    }
    .cta-button {
      background-color: #0077b6;
      border: none;
      border-radius: 5px;
      color: #fff;
      cursor: pointer;
      font-size: 18px;
      padding: 10px 20px;
      transition: background-color 0.3s ease;
    }
    .cta-button:hover {
      background-color: #005b8f;
    }
    .offers {
      background-color: #f2f2f2;
      padding: 40px 20px;
      text-align: center;
    }
    .offers h2 {
      margin-bottom: 20px;
    }
    .offer-card {
      background-color: #fff;
      border-radius: 5px;
      box-shadow: 0 2px 5px rgba(0, 0, 0, 0.1);
      margin-bottom: 20px;
      padding: 20px;
    }
    .offer-card h3 {
      margin-top: 0;
    }
    .offer-card p {
      margin-bottom: 20px;
    }
    .news {
      padding: 40px 20px;
    }
    .news h2 {
      margin-bottom: 20px;
    }
    .news-article {
      margin-bottom: 40px;
    }
    .news-article h3 {
      margin-top: 0;
    }
  </style>
</head>
<body>
  <header>
    <h1>Mister Bazinho</h1>
    <nav>
      <ul>
        <li><a href="#home">Accueil</a></li>
        <li><a href="#services">Nos services</a></li>
        <li><a href="#about">À propos</a></li>
        <li><a href="#contact">Nous contacter</a></li>
        <li><a href="#news">Actualités</a></li>
      </ul>
    </nav>
  </header>

  <main>
    <section id="home" class="hero">
      <h1>Transformez votre entreprise avec Mister Bazinho</h1>
      <p>Experts en services informatiques et marketing digital</p>
      <a href="#contact" class="cta-button">Contactez-nous</a>
    </section>

    <section id="services">
      <h2>Nos services</h2>
      <ul>
        <li>Création de comptes professionnels (Facebook, Instagram, YouTube, TikTok, etc.)</li>
        <li>Gestion de comptes sur les réseaux sociaux</li>
        <li>Réparation d'ordinateurs (hardware et software)</li>
        <li>Booster de réseaux sociaux</li>
      </ul>
    </section>

    <section id="about">
      <h2>À propos</h2>
      <p>Mister Bazinho est une entreprise spécialisée dans l'informatique et le marketing digital. Nous offrons une gamme complète de services pour vous aider à atteindre vos objectifs.</p>
      <p>Téléphone: +243 831105336</p>
      <p>Email: Misterbazinho@gmail.com</p>
      <p>Réseaux sociaux:</p>
      <ul>
        <li><a href="https://www.facebook.com/InfluenceAfricaCommunication">Facebook</a></li>
        <li><a href="https://www.instagram.com/misterbazinho">Instagram</a></li>
        <li><a href="https://youtube.com/@misterbazinhoofficiel">YouTube</a></li>
        <li><a href="https://www.tiktok.com/@mister.bazinho.pr">TikTok</a></li>
      </ul>
    </section>

    <section id="contact">
      <h2>Nous contacter</h2>
      <form>
        <label for="name">Nom :</label>
        <input type="text" id="name" name="name" required>

        <label for="email">Email :</label>
        <input type="email" id="email" name="email" required>

        <label for="message">Message :</label>
        <textarea id="message" name="message" required></textarea>

        <button type="submit" class="cta-button">Envoyer</button>
      </form>
    </section>

    <section id="news">
      <h2>Actualités</h2>
      <article class="news-article">
        <h3>Comment booster votre présence sur les réseaux sociaux</h3>
        <p>Découvrez nos conseils pour optimiser votre stratégie de marketing digital...</p>
        <a href="#" class="cta-button">Lire l'article</a>
      </article>
      <!-- Ajoutez d'autres articles de blog ici -->
    </section>

    <section class="offers">
      <h2>Nos offres de réduction</h2>
      <div class="offer-card">
        <h3>Offre 1 - 20% de réduction</h3>
        <p>Profitez de 20% de réduction sur la création de comptes professionnels.</p>
        <a href="#order" class="cta-button">Commander</a>
      </div>
      <div class="offer-card">
        <h3>Offre 2 - 15% de réduction</h3>
        <p>Obtenez 15% de réduction sur la gestion de comptes sur les réseaux sociaux.</p>
        <a href="#order" class="cta-button">Commander</a>
      </div>
    </section>

    <section id="order">
      <h2>Passer une commande</h2>
      <form>
        <label for="service">Service souhaité :</label>
        <select id="service" name="service" required>
          <option value="">Sélectionnez un service</option>
          <option value="creation-compte">Création de compte</option>
          <option value="gestion-compte">Gestion de compte</option>
          <option value="reparation-ordinateur">Réparation d'ordinateur</option>
          <option value="booster-reseaux-sociaux">Booster de réseaux sociaux</option>
        </select>

        <label for="details">Détails de la commande :</label>
        <textarea id="details" name="details" required></textarea>

        <button type="submit" class="cta-button">Passer la commande</button>
      </form>
    </section>
  </main>

  <footer>
    <p>&copy; 2023 Mister Bazinho. Tous droits réservés.</p>
  </footer>

  <script>
    // Ajout de la fonctionnalité de formulaire (optionnel)
    document.querySelector('form').addEventListener('submit', function(event) {
      event.preventDefault();
      // Traitement du formulaire ici
      console.log('Formulaire envoyé !');
    });
  </script>
</body>
</html>

Ajouter l'animation dans les ensembles pour embellir le site 
