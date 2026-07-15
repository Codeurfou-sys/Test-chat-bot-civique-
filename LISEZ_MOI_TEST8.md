# Test 8 — Inclusion récursive ChatMD

## Fichiers à déposer à la racine du dépôt GitHub

- `TEST8_CHAT_MD.md`
- `TEST8_INCLUDE_NIVEAU_1.md`
- `TEST8_INCLUDE_NIVEAU_2.md`

Les URL sont déjà configurées pour le dépôt :

`Codeurfou-sys/Test-chat-bot-civique-`

et la branche :

`main`

## URL à charger dans ChatMD

`https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST8_CHAT_MD.md`

## Interprétation

### Le bouton « Ouvrir le niveau 1 » fonctionne

L’inclusion directe fonctionne.

### Le bouton « Ouvrir le niveau 2 » fonctionne aussi

L’inclusion récursive fonctionne : un fichier inclus peut inclure un autre fichier.

### Le niveau 1 fonctionne, mais pas le niveau 2

ChatMD accepte les inclusions de premier niveau, mais ne traite pas les inclusions imbriquées dans cette configuration.

### Rien ne s’affiche

Vérifier :

- que les trois fichiers sont présents à la racine du dépôt ;
- que les noms respectent exactement les majuscules et les underscores ;
- que le dépôt est public ;
- que chaque URL Raw affiche le contenu Markdown brut ;
- qu’un ancien résultat n’est pas conservé en cache.
