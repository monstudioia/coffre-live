# Coffre du live

Point de départ du live d'enregistrement « Le vault versionné » de mon studio IA, le 5 novembre 2026.

Ce dépôt contient la structure minimale d'un coffre Obsidian versionné par Git. On le complète ensemble pendant le live.

## Le copier

1. Bouton « Use this template » en haut de cette page, puis « Create a new repository ».
2. Visibilité : **Private**. Nom : celui de ton coffre, sans espace ni accent (exemple `mon-coffre`).
3. Sur ton poste, dans le dossier où tu veux le coffre :

```bash
git clone https://github.com/<ton-compte>/<ton-coffre>.git
```

4. Dans Obsidian : « Ouvrir un dossier comme coffre », choisis le dossier cloné.

La suite se fait en direct.

## Ce qu'il y a dedans

| Chemin | Rôle |
|---|---|
| `CLAUDE.md` | Les règles que toute session Claude lit avant d'écrire ici |
| `00_PILOTAGE/CORRESPONDANCE_PROJET_VAULT.md` | Quel document de ton projet Claude vit à quel chemin du coffre |
| `.gitignore` | Exclut les fichiers d'état d'Obsidian, qui changent à chaque clic |
| `.gitattributes` | Fins de ligne normalisées, binaires marqués |

## Dossiers

```
00_PILOTAGE/        table de correspondance
10_TRAVAIL/         tes documents de référence, copies du projet Claude
60_CONVERSATIONS/   synthèses de conversations
90_ARCHIVE/         périmé, jamais supprimé
```
