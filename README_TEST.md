# Test du Coach pédagogique ChatMD

Fichier à utiliser comme URL principale :

`MON_COACH_PEDAGOGIQUE_CHATMD.md`

Variables attendues :

- `@score_global` : score total sur 25
- `@score_t1` : Principes et valeurs de la République
- `@score_t2` : Système institutionnel et politique
- `@score_t3` : Droits et devoirs
- `@score_t4` : Histoire, géographie, culture
- `@score_t5` : Vivre dans la société française

Chaque score thématique est sur 5.

La syntaxe conditionnelle utilisée est celle validée pendant les tests précédents :

`if @variable ...`
contenu
`endif`

Les destinations des boutons pourront être renommées pour correspondre exactement aux titres de sections du fichier ChatMD principal.
