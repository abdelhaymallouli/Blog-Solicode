Génère le code HTML complet de la **Page d'Accueil** en assemblant les composants statiques selon la structure ci-dessous.

## 1. Structure de Base (Le Layout)

Utilise le fichier `components/layout/layout-base.html` comme squelette de départ.

* **Titre de la page** : `<title>Accueil - [Nom de ton Projet]</title>`
* **Chemins** : Assure-toi que tous les liens (CSS, Images, JS) pointent vers la racine.

## 2. Plan d'Assemblage (Injection)

Remplace les placeholders ou sections du layout par le contenu exact de ces fichiers :

1. **Header** : Insérer `components/navigation/navbar.html`
2. **Main (Contenu)** : Assembler dans cet ordre :
* `components/sections/hero.html`
* **Grille d'articles** : Créer une section `<div class="grid">` et y insérer **3 fois** le composant `components/cards/card-article.html`.


3. **Footer** : Insérer `components/navigation/footer.html`

## 3. Contraintes Techniques

* **Zéro JS externe** : Utilise uniquement ce qui est déjà prévu (Tailwind, Lucide, Preline).
* **Rendus propres** : Nettoie les commentaires d'assemblage (ex: supprime les ``) pour ne laisser que le HTML final.
* **Format** : Le résultat doit être un fichier HTML unique, prêt à être sauvegardé sous `index.html`.

