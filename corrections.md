## A) Corriger les liens CSS (Normalize + Main)
- Vos liens CSS ne sont pas corrects (`main.css/normalize.css`)
- Veuillez mettre `normalize.css` en local dans `./css/normalize.css`
- Veuillez créer/utiliser `./css/main.css`
- Exemple attendu dans le `<head>` :
```
<link rel="stylesheet" href="./css/normalize.css">
<link rel="stylesheet" href="./css/main.css">
```

## B) Image du header : doit être cliquable et ouvrir dans un nouvel onglet
- Veuillez rendre l’image cliquable avec un lien qui ouvre l’image dans un nouvel onglet
- Exemple :
```
<a href="./img/ImageAleatoireCVHTML.png" target="_blank" rel="noopener noreferrer">
  <img src="./img/ImageAleatoireCVHTML.png" alt="Photo de Dorian Summerer">
</a>
```

## C) Footer : ajouter l’e-mail en lien `mailto:`
- Votre e-mail est affiché mais n’est pas cliquable
- Veuillez utiliser `mailto:`
- Exemple :
```
<footer>
  &copy;2025 Dorian Summerer —
  <a href="mailto:dorianmaxim.summerer@divtec.ch">dorianmaxim.summerer@divtec.ch</a>
</footer>
```

## Autres
- Projet pas publié sur GitHub pages
- Le texte alternatif `alt` doit être plus précis que "Logo"
- Pas de favicon
