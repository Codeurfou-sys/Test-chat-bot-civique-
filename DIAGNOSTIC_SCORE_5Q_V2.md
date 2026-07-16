## DS5V2_ACCUEIL

`@score = 0`
`@score_t1 = 0`
`@score_t2 = 0`
`@score_t3 = 0`
`@score_t4 = 0`
`@score_t5 = 0`

### 🧑‍🏫 Bilan de départ — Carte de résident

Ce test comporte **5 questions**.

Les thématiques ne sont pas annoncées pendant le questionnaire.

1. [▶️ Commencer](DS5V2_Q1)

## DS5V2_Q1

### Question 1 / 5

Quelle est la devise de la République française ?

1. [Liberté — Justice — Solidarité](DS5V2_Q1_FAUX)
2. [Liberté — Égalité — Fraternité](DS5V2_Q1_VRAI)
3. [Égalité — Travail — Fraternité](DS5V2_Q1_FAUX)
4. [République — Liberté — Nation](DS5V2_Q1_FAUX)

## DS5V2_Q1_VRAI

`@score = calc(@score+1)`
`@score_t1 = calc(@score_t1+1)`

✅ Bonne réponse.

La devise de la République française est **Liberté, Égalité, Fraternité**.

1. [Question suivante](DS5V2_Q2)

## DS5V2_Q1_FAUX

❌ Cette réponse n’est pas correcte.

La devise de la République française est **Liberté, Égalité, Fraternité**.

1. [Question suivante](DS5V2_Q2)

## DS5V2_Q2

### Question 2 / 5

Qui élit le président de la République française ?

1. [Les députés](DS5V2_Q2_FAUX)
2. [Les sénateurs](DS5V2_Q2_FAUX)
3. [Les citoyens français inscrits sur les listes électorales](DS5V2_Q2_VRAI)
4. [Les maires](DS5V2_Q2_FAUX)

## DS5V2_Q2_VRAI

`@score = calc(@score+1)`
`@score_t2 = calc(@score_t2+1)`

✅ Bonne réponse.

Le président de la République est élu au **suffrage universel direct**.

1. [Question suivante](DS5V2_Q3)

## DS5V2_Q2_FAUX

❌ Cette réponse n’est pas correcte.

Le président de la République est élu directement par les citoyens français inscrits sur les listes électorales.

1. [Question suivante](DS5V2_Q3)

## DS5V2_Q3

### Question 3 / 5

En France, le vote aux élections politiques est :

1. [Obligatoire](DS5V2_Q3_FAUX)
2. [Un droit, mais il n’est pas obligatoire](DS5V2_Q3_VRAI)
3. [Réservé aux élus](DS5V2_Q3_FAUX)
4. [Réservé aux personnes de plus de 25 ans](DS5V2_Q3_FAUX)

## DS5V2_Q3_VRAI

`@score = calc(@score+1)`
`@score_t3 = calc(@score_t3+1)`

✅ Bonne réponse.

Le vote est un droit civique. En France, il n’est pas obligatoire.

1. [Question suivante](DS5V2_Q4)

## DS5V2_Q3_FAUX

❌ Cette réponse n’est pas correcte.

Le vote est un droit civique et il n’est pas obligatoire en France.

1. [Question suivante](DS5V2_Q4)

## DS5V2_Q4

### Question 4 / 5

Combien la France métropolitaine compte-t-elle de régions ?

1. [13](DS5V2_Q4_VRAI)
2. [18](DS5V2_Q4_FAUX)
3. [22](DS5V2_Q4_FAUX)
4. [27](DS5V2_Q4_FAUX)

## DS5V2_Q4_VRAI

`@score = calc(@score+1)`
`@score_t4 = calc(@score_t4+1)`

✅ Bonne réponse.

La France métropolitaine compte **13 régions**.

1. [Question suivante](DS5V2_Q5)

## DS5V2_Q4_FAUX

❌ Cette réponse n’est pas correcte.

La France métropolitaine compte **13 régions**.

1. [Question suivante](DS5V2_Q5)

## DS5V2_Q5

### Question 5 / 5

À quoi sert principalement la carte Vitale ?

1. [À voter](DS5V2_Q5_FAUX)
2. [À conduire un véhicule](DS5V2_Q5_FAUX)
3. [À faciliter la prise en charge et le remboursement des dépenses de santé](DS5V2_Q5_VRAI)
4. [À payer ses impôts](DS5V2_Q5_FAUX)

## DS5V2_Q5_VRAI

`@score = calc(@score+1)`
`@score_t5 = calc(@score_t5+1)`

✅ Bonne réponse.

La carte Vitale facilite la prise en charge des soins par l’Assurance maladie.

1. [Afficher mon bilan](DS5V2_BILAN)

## DS5V2_Q5_FAUX

❌ Cette réponse n’est pas correcte.

La carte Vitale sert principalement à faciliter la prise en charge et le remboursement des dépenses de santé.

1. [Afficher mon bilan](DS5V2_BILAN)

## DS5V2_BILAN

### 🎯 Votre bilan de départ

#### Score global

**`@score` / 5**

#### Détail des résultats

- Principes et valeurs de la République : **`@score_t1` / 1**
- Système institutionnel et politique : **`@score_t2` / 1**
- Droits et devoirs : **`@score_t3` / 1**
- Histoire, géographie et culture : **`@score_t4` / 1**
- Vivre dans la société française : **`@score_t5` / 1**

`if @score == 5`

### 🏆 Profil : très bon niveau

Vous avez répondu correctement aux cinq questions.

Poursuivez avec des entraînements et des examens blancs afin de consolider vos acquis.

`endif`

`if @score >= 3 && @score < 5`

### 🎯 Profil : en progression

Vous possédez plusieurs connaissances solides.

Renforcez en priorité les thématiques signalées ci-dessous.

`endif`

`if @score < 3`

### 🌱 Profil : début de parcours

Ce résultat est un point de départ.

Nous vous recommandons de commencer par le **parcours de révision** du Guide de réussite, puis de travailler progressivement les thématiques indiquées ci-dessous.

1. [📅 Consulter le parcours de révision conseillé](DS5V2_GUIDE_DEBUTANT)

`endif`

### Recommandations par thématique

`if @score_t1 == 0`

- **Principes et valeurs de la République** : révision recommandée.

`endif`

`if @score_t2 == 0`

- **Système institutionnel et politique** : révision recommandée.

`endif`

`if @score_t3 == 0`

- **Droits et devoirs** : révision recommandée.

`endif`

`if @score_t4 == 0`

- **Histoire, géographie et culture** : révision recommandée.

`endif`

`if @score_t5 == 0`

- **Vivre dans la société française** : révision recommandée.

`endif`

`if @score == 5`

Aucune thématique prioritaire n’a été détectée dans ce test court.

`endif`

### Que souhaitez-vous faire ?

1. [🔁 Refaire le bilan](DS5V2_ACCUEIL)
2. [🏠 Retour à l’accueil]()

## DS5V2_GUIDE_DEBUTANT

### 📅 Parcours de révision conseillé

Dans la version finale, ce bouton ouvrira directement le chapitre **Construire son parcours de révision** du fichier `GUIDE_REUSSITE.md`.

Pour commencer :

1. travaillez une thématique à la fois ;
2. consultez les notions essentielles ;
3. faites un entraînement après chaque thématique ;
4. revenez ensuite effectuer un nouveau bilan.

1. [⬅️ Retour à mon bilan](DS5V2_BILAN)
2. [🔁 Refaire le bilan](DS5V2_ACCUEIL)
