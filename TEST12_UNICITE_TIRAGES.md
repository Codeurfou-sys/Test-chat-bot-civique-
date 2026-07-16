## T12_RESULTATS

### Résultat des cinq tirages

- Tirage 1 : **@{_tirage1}**
- Tirage 2 : **@{_tirage2}**
- Tirage 3 : **@{_tirage3}**
- Tirage 4 : **@{_tirage4}**
- Tirage 5 : **@{_tirage5}**

### Analyse automatique des doublons

`if @{_tirage1} == @{_tirage2}`

⚠️ Doublon détecté entre les tirages 1 et 2.

`endif`

`if @{_tirage1} == @{_tirage3}`

⚠️ Doublon détecté entre les tirages 1 et 3.

`endif`

`if @{_tirage1} == @{_tirage4}`

⚠️ Doublon détecté entre les tirages 1 et 4.

`endif`

`if @{_tirage1} == @{_tirage5}`

⚠️ Doublon détecté entre les tirages 1 et 5.

`endif`

`if @{_tirage2} == @{_tirage3}`

⚠️ Doublon détecté entre les tirages 2 et 3.

`endif`

`if @{_tirage2} == @{_tirage4}`

⚠️ Doublon détecté entre les tirages 2 et 4.

`endif`

`if @{_tirage2} == @{_tirage5}`

⚠️ Doublon détecté entre les tirages 2 et 5.

`endif`

`if @{_tirage3} == @{_tirage4}`

⚠️ Doublon détecté entre les tirages 3 et 4.

`endif`

`if @{_tirage3} == @{_tirage5}`

⚠️ Doublon détecté entre les tirages 3 et 5.

`endif`

`if @{_tirage4} == @{_tirage5}`

⚠️ Doublon détecté entre les tirages 4 et 5.

`endif`

`if @{_tirage1} != @{_tirage2} && @{_tirage1} != @{_tirage3} && @{_tirage1} != @{_tirage4} && @{_tirage1} != @{_tirage5} && @{_tirage2} != @{_tirage3} && @{_tirage2} != @{_tirage4} && @{_tirage2} != @{_tirage5} && @{_tirage3} != @{_tirage4} && @{_tirage3} != @{_tirage5} && @{_tirage4} != @{_tirage5}`

✅ Aucun doublon : les cinq questions sont différentes.

`endif`

### Comment recommencer le test ?

Les variables commencent par `_` : elles restent fixes pendant la session.

Pour obtenir un nouveau tirage :

1. rechargez complètement le chatbot ;
2. affichez de nouveau les cinq tirages ;
3. recommencez au moins dix fois ;
4. notez si des doublons apparaissent.

1. [🏠 Retour à l’accueil]()
