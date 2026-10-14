# Portfolio — Amokrane Chala

Portfolio React + Vite, en français, responsive, direction artistique expérimentale et colorée. Les fiches projets ont des URLs partageables via les hash `#projet/slug`.

## Lancer le site en local

Prérequis : Node.js LTS.

```bash
npm install
npm run dev
```

Vérifier le build de production :

```bash
npm run build
npm run preview
```

## Personnaliser avant publication

Modifie `src/data.js` :
- coordonnées, domaine et liens GitHub / LinkedIn dans `profile` ;
- titres, rôles, textes, statuts, outils et images de chaque projet ;
- compétences et parcours.

### Important : honnêteté du portfolio

Les images distantes sont des visuels temporaires provenant d’Unsplash. Remplace-les par tes propres photos, affiches et créations, ou par des visuels dont tu possèdes les droits. Les projets marqués « Concept à réaliser », « À documenter » ou « À réaliser » ne doivent pas être présentés comme des travaux terminés. Mets à jour les statuts et le contenu quand tu auras les vrais livrables.

Pour ajouter tes fichiers : crée `public/images/`, place tes images dedans puis remplace la propriété `image` du projet par exemple par `/images/mon-affiche.jpg`. Pour le CV, place le PDF final dans `public/cv-amokrane-chala.pdf` ou change `profile.cvPath`.

## Publier sur Internet

1. Crée un dépôt GitHub et pousse ce dossier.
2. Importe le dépôt dans Vercel ou Netlify.
3. Commande de build : `npm run build` ; dossier de sortie : `dist`.
4. Dans le tableau de bord du fournisseur, ajoute le domaine que tu auras acheté (par exemple `amokranchala.fr`) et suis les instructions DNS affichées par le fournisseur.
5. Vérifie le site en HTTPS, sur mobile, et les liens de contact.

Le domaine `amokranchala.fr` est un choix de travail, pas une réservation confirmée. Le site n’est pas encore publié sur Internet. L’adresse e-mail affichée est celle renseignée dans la configuration ; les liens LinkedIn et GitHub sont volontairement signalés comme à ajouter si tu n’as pas encore renseigné les URL exactes.

## Structure

- `src/main.jsx` : pages, filtres, navigation et fiches projets
- `src/data.js` : contenu personnalisable
- `src/styles.css` : design responsive, couleurs et animations
- `public/favicon.svg` : favicon
