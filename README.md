# Atelier LN-IA — Séance 06 : du prompt simple au prompt structuré

**Challenge 100 jours — Formation IA pratique**  
Module 02 · Semaine 03 · Séance 06 · Atelier pratique et production  
Pilotage : Prof. Abderrahman EL HISSE


## Accéder à l’atelier en ligne

[**Ouvrir l’atelier Séance 06 sur GitHub Pages**](https://elhisse-clprepas.github.io/atelier-seance06-ln-IA/)

Accès direct dans votre navigateur, sans installation : présentation, affiches, exercices pratiques et supports téléchargeables.

## Préparer la présentation

[**Fiche de conduite : préparation, déroulé et solution de secours**](docs/CONDUITE-PRESENTATION-SEANCE-06.md)

## Objectif

Transformer un besoin réel en un prompt structuré, obtenir et contrôler une réponse IA, demander une correction, puis conserver le fichier `02-prompts/prompt-structure-v1.md`.

Ce pack est fondé sur les huit supports originaux du ZIP de séance 06. Les démonstrations sont **fictives** et n'interrogent aucun modèle d'IA. Le test réel doit être réalisé dans l'outil IA choisi par le candidat.

## Lancer le site Vite (conseillé)

Prérequis : Node.js 20 ou plus récent et npm, VS Code.

```bash
npm install
npm run dev
```

Ouvrir l'adresse indiquée par Vite, généralement `http://localhost:5173`.

Pour produire le site statique :

```bash
npm run build
npm run preview
```

Le contenu à publier se trouve dans `dist/`.

## Consulter sans installer Node.js

Ouvrir le fichier **`APERCU-SANS-INSTALLATION.html`** à la racine du pack. Il propose la présentation, le générateur et les exercices en HTML/JavaScript autonome. Ce fichier n'est pas le livrable Vite de production, mais un aperçu fonctionnel qui facilite la consultation immédiate.

## Sommaire du site

- **Accueil** : intention et étapes de la séance.
- **Présentation** : 20 diapositives avec navigation et plein écran (flèches gauche/droite).
- **Les 6 éléments** : rôle, contexte, mission, contraintes, format et amélioration, avec exemples et erreurs courantes.
- **Démonstrations** : 4 scénarios fictifs (WhatsApp, fiche projet, checklist, page web), prompt, réponse simulée, contrôle et correction.
- **Mon atelier** : champs éditables, saisie de la vraie réponse IA, export Markdown du livrable.
- **Contrôle & bilan** : checklist d'atelier et export.
- **Flashcards** : 10 cartes de révision.
- **Séance 07** : introduction au prompt maître personnel et fiche de préparation.
- **Ressources** : huit supports originaux et déroulement suggéré.

## Méthode et fichiers

Formule utilisée dans les supports de séance 06 :

`Rôle + Contexte + Mission + Contraintes + Format attendu + Amélioration`

Le fichier exporté `prompt-structure-v1.md` contient : besoin initial, livrable choisi, contexte, prompt, réponse IA réelle, correction demandée, validation humaine, points à vérifier et preuve.

**Classement recommandé** : `challenge-100j-nom-prenom/02-prompts/prompt-structure-v1.md`.

## Déroulement pédagogique conseillé (110 min)

| Période | Activité |
|---|---|
| 0–10 min | Rappel de S05, objectifs |
| 10–30 min | Les six rubriques |
| 30–45 min | Démonstration guidée |
| 45–75 min | Construction du prompt V1 |
| 75–95 min | Test réel, contrôle, demande de correction |
| 95–110 min | Pitch 1 à 2 min, classement, préparation de S07 |

## GitHub Pages

Le fichier `vite.config.js` utilise `base: './'`, afin de générer des chemins relatifs compatibles avec un déploiement en sous-répertoire.

1. Créer un dépôt GitHub et y transférer le projet (sans `node_modules` ni `dist`).
2. Dans **Settings → Pages**, sélectionner **GitHub Actions**.
3. Pousser la branche `main`. Le workflow `.github/workflows/deploy-pages.yml` installe les dépendances, compile et déploie `dist`.
4. Examiner le site publié et tester les téléchargements de fichiers.

## Notes sur les sources

Les supports d'origine sont conservés dans `public/supports/`, sans réécriture. Certains sont indiqués « BROUILLON - À RELIRE » ou comportent des versions historiques. L'organisation retenue suit la clarification de pilotage : **Module 02 sur deux semaines, semaines 03 et 04 ; séance 06 en semaine 03**. Le dossier de travail de la séance 06 est `02-prompts/` conformément au support candidats joint.

## Confidentialité et pédagogie

- Le site fonctionne sans API d'IA ni connexion à un compte externe. Les démonstrations sont des exemples fictifs.
- Le brouillon du générateur est conservé dans le stockage local du navigateur lorsque celui-ci l'autorise. Pour le supprimer, utiliser le bouton « Réinitialiser » ou vider les données du navigateur.
- Relire le contenu avant de le transmettre. Éviter de saisir des données personnelles ou confidentielles dans les outils IA.
- Une réponse de l'IA n'est pas une preuve de vérité ; les candidats réalisent leur propre contrôle.

## Licence pédagogique

Matériel préparé pour l'atelier LN-IA. Supports originaux inclus à des fins de continuité de travail dans le Challenge 100 jours.

## Affiches et passage à la pratique

Quatre affiches accompagnent les 20 diapositives, dans le site et l’aperçu sans installation :
- Diapositive 1 : Module 02, semaine 03 — situer l’objectif de production.
- Diapositive 3 : parcours des séances 05 à 08 — préciser que le module couvre les semaines 03 et 04 ; l’ancien calendrier de l’affiche est contextualisé.
- Diapositive 14 : atelier du prompt structuré — choisir un besoin réel et ouvrir « Mon atelier » pour produire, tester, corriger et exporter.
- Diapositive 20 : séance 07 — préparer profil, objectifs et livrables à partir de la pratique de S06. COMMENCER-ICI.md est une référence au pack S07.

Les affiches sont conservées entières, avec texte alternatif, légende et lien pour les ouvrir en grand. En mode projection, la diapositive peut défiler. Sur mobile, l’affiche suit la consigne. Les copies publiées sont dans public/affiches ; les originaux du dossier Affiches restent inchangés.
