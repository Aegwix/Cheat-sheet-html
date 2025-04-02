# Structure de base d’un document HTML

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site web</title>
    <link rel="stylesheet" href="styles.css">
</head>
<body>
    <header>
        <h1>Bienvenue sur mon site</h1>
    </header>
    
    <nav>
        <ul>
            <li><a href="#">Accueil</a></li>
            <li><a href="#">À propos</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </nav>

    <main>
        <section>
            <h2>Section principale</h2>
            <p>Ceci est un paragraphe dans la section principale.</p>
        </section>
        
        <article>
            <h2>Article intéressant</h2>
            <p>Ceci est un article indépendant du reste du contenu.</p>
        </article>
    </main>

    <aside>
        <h2>Infos complémentaires</h2>
        <p>Voici du contenu supplémentaire.</p>
    </aside>

    <footer>
        <p>&copy; 2025 Mon Site Web. Tous droits réservés.</p>
    </footer>
</body>
</html>
```
