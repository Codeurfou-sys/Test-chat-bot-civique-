# TEST 12 — Unicité de cinq tirages aléatoires

## Objectif

Vérifier si ChatMD empêche automatiquement les doublons lorsque cinq variables fixes utilisent exactement la même liste de questions.

## Fichiers à déposer à la racine du dépôt

- `TEST12_CHAT_MD.md`
- `TEST12_UNICITE_TIRAGES.md`

## URL à charger dans ChatMD

`https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST12_CHAT_MD.md`

## Protocole conseillé

1. Ouvrir le test.
2. Afficher les cinq tirages.
3. Faire une capture ou noter la série.
4. Recharger complètement le chatbot.
5. Répéter au moins dix fois.

## Interprétation

### Des doublons apparaissent

ChatMD effectue cinq tirages indépendants sans garantir l’unicité.

Dans ce cas, il faudra utiliser :

- des séries précomposées ;
- ou une logique supplémentaire d’exclusion, si elle est documentée.

### Aucun doublon après plusieurs essais

Cela ne prouve pas encore formellement une garantie d’unicité, mais rend cette hypothèse plausible.

Pour une conclusion solide, effectuer au moins vingt à trente rechargements.

## Important

Avec cinq tirages indépendants parmi cinq valeurs, la probabilité d’obtenir les cinq valeurs toutes différentes par hasard est faible.

Si ChatMD ne gère pas l’unicité, des doublons devraient apparaître rapidement.
