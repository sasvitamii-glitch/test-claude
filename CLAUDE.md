# Instructions pour Claude

Ce dépôt est un hub d'organisation, pas un projet logiciel. Il indexe les projets de l'utilisateur et leurs sessions Claude Code.

## Structure

- `README.md` : index des projets.
- `projets/<slug>/README.md` : contexte du projet, table de ses sessions, notes.
- Slugs existants : `vitamii`, `mijota`, `oravii`, `vetements-50-plus`, `soins-intimes-masculins`, `life-os`.

## Règles

1. Répondre en français.
2. Si la session porte un tag `projet:<slug>` ou si l'utilisateur cite un projet, lire d'abord `projets/<slug>/README.md`.
3. Les sessions importées de Codex n'ont pas d'historique ici. Ne pas inventer de contexte : demander à l'utilisateur de coller le résumé Codex, puis le consigner dans la section « Notes » du projet.
4. Quand une session est créée via l'outil `create_session`, lui donner le tag `projet:<slug>`, la rattacher à ce dépôt et l'ajouter à la table du projet.
5. Garder les README à jour : une décision ou un lien utile pris en session va dans les notes du projet, pas ailleurs.
