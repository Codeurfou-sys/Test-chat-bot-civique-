## DS5_ACCUEIL

### 🧑‍🏫 Bilan de départ — Carte de résident

Ce test comporte **5 questions**.

Les thématiques ne sont pas annoncées pendant le questionnaire.

Une bonne réponse ajoute :

- 1 point au score global ;
- 1 point au sous-score de la thématique correspondante.

1. [▶️ Commencer @score=0 @score_t1=0 @score_t2=0 @score_t3=0 @score_t4=0 @score_t5=0](DS5_Q1)

## DS5_Q1

### Question 1 / 5

Quelle est la devise de la République française ?

1. [Liberté — Justice — Solidarité](DS5_Q1_FAUX)
2. [Liberté — Égalité — Fraternité @score=calc(@score+1) @score_t1=calc(@score_t1+1)](DS5_Q1_VRAI)
3. [Égalité — Travail — Fraternité](DS5_Q1_FAUX)
4. [République — Liberté — Nation](DS5_Q1_FAUX)

## DS5_Q1_VRAI

✅ Bonne réponse.

La devise de la République française est **Liberté, Égalité, Fraternité**.

1. [Question suivante](DS5_Q2)

## DS5_Q1_FAUX

❌ Cette réponse n’est pas correcte.

La devise de la République française est **Liberté, Égalité, Fraternité**.

1. [Question suivante](DS5_Q2)

## DS5_Q2

### Question 2 / 5

Qui élit le président de la République française ?

1. [Les députés](DS5_Q2_FAUX)
2. [Les sénateurs](DS5_Q2_FAUX)
3. [Les citoyens français inscrits sur les listes électorales @score=calc(@score+1) @score_t2=calc(@score_t2+1)](DS5_Q2_VRAI)
4. [Les maires](DS5_Q2_FAUX)

## DS5_Q2_VRAI

✅ Bonne réponse.

Le président de la République est élu au **suffrage universel direct**.

1. [Question suivante](DS5_Q3)

## DS5_Q2_FAUX

❌ Cette réponse n’est pas correcte.

Le président de la République est élu directement par les citoyens français inscrits sur les listes électorales.

1. [Question suivante](DS5_Q3)

## DS5_Q3

### Question 3 / 5

En France, le vote aux élections politiques est :

1. [Obligatoire](DS5_Q3_FAUX)
2. [Un droit, mais il n’est pas obligatoire @score=calc(@score+1) @score_t3=calc(@score_t3+1)](DS5_Q3_VRAI)
3. [Réservé aux élus](DS5_Q3_FAUX)
4. [Réservé aux personnes de plus de 25 ans](DS5_Q3_FAUX)

## DS5_Q3_VRAI

✅ Bonne réponse.

Le vote est un droit civique. En France, il n’est pas obligatoire.

1. [Question suivante](DS5_Q4)

## DS5_Q3_FAUX

❌ Cette réponse n’est pas correcte.

Le vote est un droit civique et il n’est pas obligatoire en France.

1. [Question suivante](DS5_Q4)

## DS5_Q4

### Question 4 / 5

Combien la France métropolitaine compte-t-elle de régions ?

1. [13 @score=calc(@score+1) @score_t4=calc(@score_t4+1)](DS5_Q4_VRAI)
2. [18](DS5_Q4_FAUX)
3. [22](DS5_Q4_FAUX)
4. [27](DS5_Q4_FAUX)

## DS5_Q4_VRAI

✅ Bonne réponse.

La France métropolitaine compte **13 régions**.

1. [Question suivante](DS5_Q5)

## DS5_Q4_FAUX

❌ Cette réponse n’est pas correcte.

La France métropolitaine compte **13 régions**.

1. [Question suivante](DS5_Q5)

## DS5_Q5

### Question 5 / 5

À quoi sert principalement la carte Vitale ?

1. [À voter](DS5_Q5_FAUX)
2. [À conduire un véhicule](DS5_Q5_FAUX)
3. [À faciliter la prise en charge et le remboursement des dépenses de santé @score=calc(@score+1) @score_t5=calc(@score_t5+1)](DS5_Q5_VRAI)
4. [À payer ses impôts](DS5_Q5_FAUX)

## DS5_Q5_VRAI

✅ Bonne réponse.

La carte Vitale facilite la prise en charge des soins par l’Assurance maladie.

1. [Afficher mon bilan](DS5_BILAN)

## DS5_Q5_FAUX

❌ Cette réponse n’est pas correcte.

La carte Vitale sert principalement à faciliter la prise en charge et le remboursement des dépenses de santé.

1. [Afficher mon bilan](DS5_BILAN)

## DS5_BILAN

### 🎯 Votre bilan de départ

#### Score global

**@score / 5**

#### Détail des résultats

- Principes et valeurs de la République : **@score_t1 / 1**
- Système institutionnel et politique : **@score_t2 / 1**
- Droits et devoirs : **@score_t3 / 1**
- Histoire, géographie et culture : **@score_t4 / 1**
- Vivre dans la société française : **@score_t5 / 1**

`if @score == 5`

### 🏆 Profil : très bon niveau

Vous avez répondu correctement aux cinq questions.

Poursuivez avec des entraînements et des examens blancs afin de consolider vos acquis.

`endif`

`if @score >= 3`

`if @score < 5`

### 🎯 Profil : en progression

Vous possédez plusieurs connaissances solides.

Les résultats détaillés ci-dessous permettent d’identifier les thématiques à renforcer.

`endif`

`endif`

`if @score < 3`

### 🌱 Profil : début de parcours

Ce résultat est un point de départ.

Commencez par revoir les cours et les notions essentielles, puis refaites un bilan après quelques séances.

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

1. [🔁 Refaire le bilan](DS5_RESET)
2. [🏠 Retour à l’accueil]()

## DS5_RESET

Les scores vont être remis à zéro.

1. [▶️ Recommencer @score=0 @score_t1=0 @score_t2=0 @score_t3=0 @score_t4=0 @score_t5=0](DS5_Q1)
2. [🏠 Retour à l’accueil]()
