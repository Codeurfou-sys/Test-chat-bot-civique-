# Test Diagnostic V1

## Fichiers à déposer à la racine du dépôt

- `TEST_DIAGNOSTIC_CHAT_MD.md`
- `DIAGNOSTIC_V1.md`

## URL à charger dans ChatMD

`https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST_DIAGNOSTIC_CHAT_MD.md`

## Ce que ce test valide

1. Ouverture de Mon Coach pédagogique.
2. Choix de l’examen.
3. Deux questions de positionnement.
4. Enchaînement de cinq QCM.
5. Feedback différent pour une bonne ou une mauvaise réponse.
6. Arrivée au bilan final.

## Important

`obfuscate: true` est placé dans le fichier principal, car ChatMD n’interprète pas le YAML des fichiers inclus.

Le score automatique n’est volontairement pas encore intégré. Pour l’ajouter sans inventer de syntaxe, il faudra relever dans la documentation officielle la syntaxe exacte :

- de création d’une variable modifiable ;
- d’incrémentation ;
- de condition ;
- d’affichage de la valeur.
