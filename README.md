<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>SanFe - Agriculture Durable</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <header>
        <h1>SanFe</h1>
        <p>Une agriculture durable et responsable</p>
    </header>

    <nav>
        <ul>
            <li><a href="#about">À propos</a></li>
            <li><a href="#cultures">Nos cultures</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>

    <section id="about">
        <h2>À propos de SanFe</h2>
        <p>SanFe est une entreprise agricole spécialisée dans la culture de l’hévéa et du cacao, avec un engagement fort envers la durabilité et l’innovation.</p>
    </section>

    <section id="cultures">
        <h2>Nos cultures</h2>
        <div class="culture">
            <h3>Hévéa</h3>
            <p>Production de caoutchouc naturel avec des pratiques respectueuses de l’environnement.</p>
        </div>
        <div class="culture">
            <h3>Cacao</h3>
            <p>Un cacao de qualité, cultivé avec soin pour une production durable.</p>
        </div>
    </section>

    <section id="contact">
        <h2>Contactez-nous</h2>
        <form>
            <label for="name">Nom :</label>
            <input type="text" id="name" name="name" required>

            <label for="email">Email :</label>
            <input type="email" id="email" name="email" required>

            <label for="message">Message :</label>
            <textarea id="message" name="message" required></textarea>

            <button type="submit">Envoyer</button>
        </form>
    </section>

    <footer>
        <p>© 2025 SanFe. Tous droits réservés.</p>
    </footer>
</body>
</html>
