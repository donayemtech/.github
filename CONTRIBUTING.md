# Guide de contribution — Donayem Tech

Bienvenue dans l'équipe ! Ces règles s'appliquent à tous les projets de l'organisation **Donayem Tech**. Elles servent à travailler proprement, à plusieurs, sans casser le travail des autres.

## 1. Équipes
WEB · MOBILE · MARKETING · STAGE · FORMATION · DESIGN. Chaque projet est rattaché à l'équipe concernée. En cas de doute, demandez au responsable de l'équipe.

## 2. Règles de travail
1. **Une tâche = une branche.** On ne travaille jamais directement sur `main`.
2. **Nom des branches :** `type/description-courte`, par exemple `feature/page-contact`, `fix/erreur-paiement`, `docs/readme`.
3. **Messages de commit clairs**, en français ou en anglais, à l'impératif : « Ajoute le formulaire de contact ».
4. **Pull request obligatoire** pour tout changement vers `main`, avec au moins **1 relecture approuvée** avant la fusion.
5. **Petites pull requests** : une PR traite un seul sujet.
6. **Pas de secrets dans le code :** jamais de mots de passe, clés API, fichiers `.env` ni données clients. Utiliser des variables d'environnement.
7. **Tester avant de proposer** : le projet doit se lancer sans erreur et les fonctions modifiées doivent être vérifiées.
8. **Code lisible** : noms explicites, pas de code commenté inutile, respect de la structure du projet.
9. **Respect et entraide** : on relit avec bienveillance, on explique ses remarques, on répond dans les 48 h ouvrées.
10. **Sécurité du compte :** activer l'authentification à deux facteurs sur son compte GitHub.
11. **Confidentialité :** les dépôts clients restent privés. On ne partage pas le code d'un client en dehors de l'équipe.

## 3. Déroulement d'une contribution
1. Récupérer la dernière version : `git checkout main && git pull`
2. Créer sa branche : `git checkout -b feature/ma-tache`
3. Coder, puis valider : `git add . && git commit -m "Ajoute ..."`
4. Envoyer la branche : `git push -u origin feature/ma-tache`
5. Ouvrir une **pull request** vers `main` en remplissant le modèle.
6. Corriger selon les remarques, puis attendre l'approbation avant de fusionner.
7. Supprimer la branche après la fusion.

## 4. Relecture
Le relecteur vérifie : que le code fait ce qui est annoncé, qu'il n'y a pas de secret ou de donnée sensible, que le projet fonctionne, et que le style est cohérent.

## 5. Signaler un problème
Ouvrir une *issue* avec : ce qui était attendu, ce qui s'est passé, et les étapes pour reproduire.

## Contact
contact@donayemtech.com
