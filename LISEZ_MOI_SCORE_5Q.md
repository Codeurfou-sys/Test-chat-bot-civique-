# Test du calcul des scores — 5 questions

## Fichiers à déposer à la racine du dépôt GitHub

- `TEST_SCORE_5Q_CHAT_MD.md`
- `DIAGNOSTIC_SCORE_5Q.md`

## URL à charger dans ChatMD

`https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST_SCORE_5Q_CHAT_MD.md`

## Syntaxes testées

Le fichier principal active :

```yaml
contenuDynamique: true
obfuscate: true
```

Une bonne réponse utilise une affectation cachée dans le bouton :

```markdown
[Bonne réponse @score=calc(@score+1)](REPONSE_CORRECTE)
```

Les variables sont affichées avec :

```markdown
@score
```

Les recommandations utilisent :

```markdown
`if @score < 3`
Contenu conditionnel
`endif`
```

## Tests conseillés

### Test A — 5 bonnes réponses

Résultat attendu :

- score global : 5 / 5 ;
- chaque thématique : 1 / 1 ;
- profil « très bon niveau ».

### Test B — 3 bonnes réponses

Résultat attendu :

- score global : 3 / 5 ;
- profil « en progression » ;
- recommandations uniquement pour les thématiques ratées.

### Test C — 0 à 2 bonnes réponses

Résultat attendu :

- profil « début de parcours » ;
- recommandations pour chaque thématique ratée.

### Test D — Recommencer

Cliquer sur « Refaire le bilan », puis vérifier que tous les scores reviennent à zéro.
