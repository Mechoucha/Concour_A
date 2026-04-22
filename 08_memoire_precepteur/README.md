# Mémoire du précepteur — source de vérité

Ce dossier contient la **mémoire persistante** du précepteur (Claude) pour l'accompagnement de Camélia.

**Objectif** : que la mémoire suive le dépôt Git, et pas la machine. Si Camélia ouvre le projet sur un autre poste (ou si son mari le clone ailleurs), le précepteur retrouve immédiatement tout le contexte nécessaire.

## Contenu

| Fichier | Type | Rôle |
|---|---|---|
| `INDEX.md` | index | Table des matières — à lire en premier à chaque session |
| `user_camelia.md` | user | Profil Camélia (parcours, motivation, contraintes) |
| `project_preceptorat.md` | project | Nature du projet et rôle du précepteur |
| `feedback_pedagogie.md` | feedback | Méthodes pédagogiques à appliquer systématiquement |
| `feedback_cap_concours.md` | feedback | Garder le cap : pas de chantier hors épreuves |
| `feedback_cloture_session.md` | feedback | Commit + push à chaque fin de séance |

## Protocole pour le précepteur

Au **démarrage de chaque session** :
1. Lire `CLAUDE.md` à la racine du dépôt.
2. Lire `08_memoire_precepteur/INDEX.md` puis les fiches référencées.
3. Lire `01_programme/cadre.md` pour le contexte concours.
4. Lire les dernières entrées de `02_suivi/journal.md` pour savoir où on en est.

À la **clôture de chaque session** :
- Si une nouvelle préférence/règle émerge, créer une fiche ici et la référencer dans `INDEX.md`.
- Commit + push (cf. `feedback_cloture_session.md`).
