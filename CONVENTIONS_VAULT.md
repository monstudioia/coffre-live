# Conventions du coffre

## Frontmatter

Chaque note commence par :

---
type: reference
statut: actif
date_maj: 2026-11-05
tags: []
---

## Types de note

- `reference` : copie d'un document du projet Claude, écrite par le miroir, dans `10_TRAVAIL/`.
- `conversation` : synthèse d'une conversation, écrite par `/sauvegarde`, dans `60_CONVERSATIONS/`. Champs en plus : `source`, `projet`, `date_conv`, `lien`.
- `note` : tout ce que tu écris toi-même.

## Statut

- `actif` : en usage.
- `obsolete` : périmé. Le fichier part dans `90_ARCHIVE/`, il n'est jamais supprimé.

## Noms de fichiers

- Pas d'espace : des tirets.
- Conversations : `AAAA-MM-JJ-sujet.md`.
- Un fichier ne se renomme pas, ça casse les liens.
