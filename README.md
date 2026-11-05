# Maison Ravive

Site de **Le Tableau Vivant, par LMOH Photography**, publié sur https://maisonravive.fr (GitHub Pages).

## Redirections des tableaux

Chaque repère pointe vers `https://maisonravive.fr/f/CODE`.

- Nouveau tableau : copier `f/_modele.html` dans `f/CODE/index.html`, puis y mettre le lien de la vidéo du client.
- Changer de film : modifier seulement le lien dans `f/CODE/index.html`.
- `f/demo` sert aux tests du repère.

Ne jamais supprimer ni renommer un dossier `f/CODE` : le tableau correspondant ne fonctionnerait plus.

## Avant l'ouverture au public

Le site est en `noindex` (balise robots et `robots.txt`). Retirer les deux une fois les prix, délais, CGV et mentions légales validés.

## Liens partenaires (commissions)

- Lien d'un partenaire : `https://maisonravive.fr/p/CODE` (ou `https://maisonravive.fr/?p=CODE`).
- Nouveau partenaire : copier `p/_modele.html` dans `p/CODE/index.html` et remplacer CODE.
- Le code est gardé 90 jours sur le téléphone ou l'ordinateur du visiteur. Toute demande envoyée depuis le site (tableau, petit cadre, entreprise, partenaire) se termine par « Partenaire : CODE ».
- Si le visiteur passe par deux liens partenaires, c'est le dernier qui compte.

## Tableau livré avant son film

Copier `f/_attente.html` dans `f/CODE/index.html` : le repère ouvre la page « Votre film arrive bientôt ». Quand le film est prêt, remplacer par `f/_modele.html` avec le lien.
