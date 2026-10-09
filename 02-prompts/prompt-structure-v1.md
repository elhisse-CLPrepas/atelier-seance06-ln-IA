# Prompt structur? V1 ? S?ance 06

Date : 9 octobre 2026. Outil IA : Codex, dans la conversation ayant demand? le contr?le de ce dossier.

## Livrable choisi
Rapport de contr?le technique et p?dagogique du dossier atelier-seance-06-ln-ia.

## Besoin de d?part
L?utilisateur souhaite analyser le dossier, lire son README et ex?cuter les instructions pour produire les livrables demand?s. Ce besoin r?el sert de cas pratique ; aucun profil candidat n?est invent?.

## Public et utilit?
Public : responsable de l?atelier et candidats. Utilit? : conna?tre les ?l?ments pr?sents, les d?fauts corrig?s et les contr?les restant ? effectuer.

## Prompt structur?
```text
Tu es un assistant de contr?le technique et p?dagogique.

Contexte :
Le dossier local atelier-seance-06-ln-ia contient un site Vite et des supports de la s?ance 06 du Challenge 100 jours. Le README d?crit les r?sultats attendus.

Mission :
Produis un rapport de contr?le exploitable ? partir du README, du support candidats et des fichiers r?ellement pr?sents.

Contraintes :
- ?cris en fran?ais, avec des constats v?rifiables.
- Distingue les contr?les ex?cut?s, les corrections et les v?rifications restantes.
- N?invente ni r?sultat de compilation, ni validation humaine, ni publication.

Format attendu :
Un document Markdown avec constats, contr?les, corrections et prochaines v?rifications.

Am?lioration :
Propose trois am?liorations et signale les points que l?utilisateur doit v?rifier lui-m?me.
```

## R?ponse IA obtenue ? premi?re version
R?ponse produite par Codex dans cette session ? partir des lectures et commandes r?elles :

Le dossier contient les huit supports annonc?s, les sources Vite, l?aper?u autonome, les exemples et le workflow GitHub Pages. Les donn?es export?es comportent 20 diapositives, 4 d?monstrations, 10 flashcards et 6 ?l?ments de prompt. Les contr?les de syntaxe de main.js, data.js et du script autonome passent. Node.js 24.12.0 est disponible. Le lanceur npm.ps1 est bloqu? par la politique PowerShell ; npm.cmd permet de lancer npm. La copie ne d?clenchait pas sa m?thode de secours en l?absence de navigator.clipboard. Cette fonction a ?t? corrig?e dans les deux versions. Aucun d?p?t Git local n?a ?t? trouv?.

Trois am?liorations propos?es :
1. Conserver le livrable de s?ance dans 02-prompts.
2. Consigner les v?rifications dans un rapport dat?.
3. Tester la navigation et les t?l?chargements dans un navigateur avant publication.

## Correction demand?e
Consigne de relecture appliqu?e par Codex : ? Rends le bilan v?rifiable. S?pare syntaxe, compilation et test navigateur. Pr?cise que la r?ponse vient de cette session Codex et laisse la validation humaine ? l?utilisateur. Ne pr?sente pas une pr?paration comme une publication effective. ?

## R?ponse corrig?e
Le rapport final est conserv? dans docs/RAPPORT-CONTROLE-SEANCE-06.md. Il distingue les preuves techniques disponibles et les limites. Ce test IA est r?alis? dans la pr?sente session Codex ; il ne provient pas des d?monstrations fictives du site et ne constitue pas une seconde ex?cution ind?pendante du prompt. La relecture et la correction sont r?alis?es par la m?me IA ; la validation humaine reste ? effectuer.

## Validation humaine
? v?rifier par l?utilisateur. Aucune validation humaine n?est revendiqu?e par l?IA.

## Points ? v?rifier par moi-m?me
- Ouvrir le site et contr?ler son affichage sur ordinateur et mobile.
- Tester navigation, copie, export Markdown, stockage local, r?initialisation et t?l?chargements des huit supports.
- Confirmer que le cas pratique r?pond ? mon besoin et adapter mon identit? et mon portfolio si n?cessaire.
- Relire les supports historiques marqu?s brouillon avant diffusion.

## Preuve et classement
- Fichier : 02-prompts/prompt-structure-v1.md.
- Rapport : docs/RAPPORT-CONTROLE-SEANCE-06.md.
- Historique : conversation Codex du 9 octobre 2026 et sorties des commandes ; aucune capture ni URL publique cr??e.

## Pitch de s?ance
Mon livrable est un rapport de contr?le du dossier. Le prompt d?finit un r?le de contr?leur, le contexte local et une mission pr?cise. Les contraintes imposent des constats v?rifiables et l?absence de r?sultats invent?s. Le format est Markdown. La correction distingue les tests techniques de la validation humaine.
