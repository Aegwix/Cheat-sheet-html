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

# Commandes de base en HTML

## 1. Structure de base

```html
<!DOCTYPE html>
<html lang="fr">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Mon site web</title>
</head>
<body>
    <h1>Bienvenue</h1>
    <p>Ceci est un paragraphe.</p>
```

## 2. Titres et textes
 ```html
    <h1>Titre principal</h1>
    <h2>Sous-titre</h2>
    <p>Paragraphe avec du <strong>texte en gras</strong> et du <em>texte en italique</em>.</p>
```

## 3. Liens et images
```html
    <a href="https://www.exemple.com">Clique ici</a>
    <img src="image.jpg" alt="Description de l'image">
```

## 4. Listes
##### Liste non ordonnée
 ```html
   <ul>
    <li>Élément 1</li>
    <li>Élément 2</li>
   </ul>
```
##### Liste ordonnée
 ```html
   <ol>
    <li>Premier élément</li>
    <li>Deuxième élément</li>
   </ol>
```

## 5. Tableaux
```html
<table>
    <tr>
        <th>Nom</th>
        <th>Âge</th>
    </tr>
    <tr>
        <td>Nom</td>
        <td>age</td>
    </tr>
</table>
```

## 6. Formulaires
```html
<form action="/envoyer" method="post">
    <label for="nom">Nom :</label>
    <input type="text" id="nom" name="nom">
    <button type="submit">Envoyer</button>
</form>
```
