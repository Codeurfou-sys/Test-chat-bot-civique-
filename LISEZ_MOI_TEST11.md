# TEST 11 — Tirage aléatoire ChatMD

## Objectif

Vérifier deux points avant de construire la banque du diagnostic :

1. une variable aléatoire peut-elle servir de cible à un bouton ?
2. une variable sans préfixe `_` est-elle tirée de nouveau lorsque le message est réaffiché ?

## Fichiers à déposer à la racine du dépôt

- `TEST11_CHAT_MD.md`
- `TEST11_QUESTIONS_ALEATOIRES.md`

## URL à charger dans ChatMD

`https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST11_CHAT_MD.md`

## Tests à réaliser

### Test A — Variable dynamique

1. Cliquer sur « Tester un nouveau tirage à chaque affichage ».
2. Noter l’identifiant obtenu : Q1, Q2, Q3, Q4 ou Q5.
3. Cliquer sur « Effectuer un nouveau tirage ».
4. Répéter dix fois.

Résultat recherché : les identifiants doivent varier.

### Test B — Variable fixe

1. Revenir à l’accueil.
2. Cliquer plusieurs fois sur « Tester un tirage fixe pendant la session ».
3. Vérifier si la même question revient toujours.
4. Recharger entièrement le chatbot.

Résultat recherché : le tirage reste stable dans la session, mais peut changer après rechargement.

## Interprétation

- Si la variable dynamique fonctionne comme cible et varie à chaque réaffichage, nous pourrons envisager un nouveau tirage lorsque l’apprenant recommence.
- Si seule la variable fixe fonctionne comme cible, nous pourrons varier le diagnostic à chaque nouveau chargement, mais pas nécessairement avec le bouton « Refaire ».
- Ce test ne garantit pas encore cinq questions distinctes : cinq tirages indépendants peuvent produire des doublons.
