# Correction du test de score

## Cause du problème précédent

Deux syntaxes étaient incorrectes :

1. Le YAML utilisait `contenuDynamique: true`, alors que l’option documentée est :

```yaml
variablesDynamiques: true
```

2. Les affectations étaient placées dans le texte des boutons. Elles doivent être exécutées dans les blocs de réponse :

```markdown
`@score = calc(@score+1)`
```

3. Pour afficher une variable dynamique dans un message, elle doit être placée entre accents graves :

```markdown
`@score`
```

## Fichiers

- `TEST_SCORE_5Q_V2_CHAT_MD.md`
- `DIAGNOSTIC_SCORE_5Q_V2.md`

## Tests à réaliser

- 5 bonnes réponses ;
- 3 bonnes réponses ;
- 0 bonne réponse ;
- refaire le bilan après un premier passage.
