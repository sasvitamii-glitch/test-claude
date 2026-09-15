# Espace de travail Claude Code

Hub d'organisation des projets, migré depuis Codex le 15 septembre 2026 : 6 projets, 21 sessions.
Ce dépôt ne contient pas de code applicatif : chaque dossier de `projets/` porte le contexte d'un projet et la liste de ses sessions Claude Code.

| Projet | Dossier | Sessions | Tag |
|---|---|---|---|
| Vitamii | [`projets/vitamii/`](projets/vitamii/README.md) | 14 | `projet:vitamii` |
| Mijota | [`projets/mijota/`](projets/mijota/README.md) | 1 | `projet:mijota` |
| Oravii | [`projets/oravii/`](projets/oravii/README.md) | 2 | `projet:oravii` |
| Vêtements 50+ | [`projets/vetements-50-plus/`](projets/vetements-50-plus/README.md) | 1 | `projet:vetements-50-plus` |
| Soins intimes masculins | [`projets/soins-intimes-masculins/`](projets/soins-intimes-masculins/README.md) | 2 | `projet:soins-intimes-masculins` |
| Life OS | [`projets/life-os/`](projets/life-os/README.md) | 1 | `projet:life-os` |

## Conventions

- Une session Claude Code = un sujet de travail. Elle porte le tag `projet:<slug>` de son projet, et `source:codex` si elle vient de Codex.
- Le tag `codex:en-cours` marque les sessions qui tournaient encore sur Codex au moment de la migration.
- Les sessions sont rattachées à ce dépôt : `CLAUDE.md` est chargé à l'ouverture et renvoie Claude vers le README du projet concerné.
- Le README d'un projet est la source de vérité : contexte, sessions, notes.

## Ajouter un projet ou une session

1. Projet : créer `projets/<slug>/README.md` sur le même modèle et ajouter une ligne dans la table ci-dessus.
2. Session : la créer dans Claude Code avec le tag `projet:<slug>`, puis l'ajouter à la table du projet.
