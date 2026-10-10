# Prompt structuré V1 — Séance 06

Date initiale : 9 octobre 2026. Suivi : 10 octobre 2026. Outil IA : Codex.

## Livrable choisi
Rapport de contrôle technique et pédagogique du dossier atelier-seance-06-ln-ia.

## Besoin de départ
Analyser le dossier, lire ses instructions, exécuter les contrôles et identifier le travail restant.

## Public et utilité
Responsable de l’atelier et candidats : disposer de constats vérifiables et d’une liste de vérifications restantes.

## Prompt structuré
```text
Tu es un assistant de contrôle technique et pédagogique.

Contexte :
Le dossier contient un site Vite et des supports de la séance 06. Le README décrit les résultats attendus.

Mission :
Produis un rapport de contrôle à partir des instructions et des fichiers réellement présents.

Contraintes :
- Écris en français avec des constats vérifiables.
- Distingue contrôles exécutés, corrections et vérifications restantes.
- N’invente ni résultat de compilation, ni validation humaine, ni publication.

Format attendu :
Un document Markdown avec constats, preuves et prochaines étapes.

Amélioration :
Propose trois améliorations et les points à vérifier par l’utilisateur.
```

## Réponse IA obtenue — synthèse historique
Au contrôle initial du 9 octobre, les sources et supports étaient présents et la compilation réussissait. Aucun dépôt Git n’avait encore été initialisé à ce stade. Le dépôt a ensuite été créé et le commit 548d082 publié sur GitHub.

## Correction demandée
Distinguer la compilation de la recette navigateur, conserver des preuves vérifiables et laisser la validation humaine au responsable. Actualiser les constats Git après publication.

## Réponse corrigée — suivi du 10 octobre
Le rapport docs/RAPPORT-CONTROLE-SEANCE-06.md consigne les preuves disponibles. Le dépôt était propre avant les corrections de cet audit. L’audit npm ne signale aucune vulnérabilité. La publication a échoué car Pages n’est pas activé. Les accents des messages et le workflow ont été corrigés localement. La recette navigateur reste à effectuer : la connexion de contrôle a échoué avant ouverture du site.

La réponse et sa relecture proviennent de la même session d’assistance ; elles ne constituent pas une validation indépendante.

## Trois améliorations
1. Conserver les contrôles dans un rapport daté.
2. Installer les dépendances depuis le verrou avec npm ci.
3. Effectuer une recette navigateur avant diffusion.

## Validation humaine
À effectuer par l’utilisateur. Aucune validation humaine n’est revendiquée.

## Points à vérifier
- Navigation, mobile, copie, export, brouillon, réinitialisation et téléchargements.
- Exactitude des supports historiques et adéquation au besoin.
- Activation Pages, déploiement réussi et contrôle public.
- Classement de la preuve dans le portfolio.

## Preuve et classement
- Livrable : 02-prompts/prompt-structure-v1.md.
- Rapport : docs/RAPPORT-CONTROLE-SEANCE-06.md.
- Conversation et sorties des commandes des 9 et 10 octobre 2026.
- Aucune capture actuelle ni publication réussie ne sont revendiquées.

## Pitch de séance
Le livrable est un rapport de contrôle du dossier. Les six rubriques cadrent la mission et imposent des preuves. La correction sépare les tests techniques de la recette et de la validation humaine.
