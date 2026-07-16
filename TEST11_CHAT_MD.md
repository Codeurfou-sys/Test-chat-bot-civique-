---
obfuscate: true
variables:
  questionAleatoire:
    - "T11_Q1"
    - "T11_Q2"
    - "T11_Q3"
    - "T11_Q4"
    - "T11_Q5"
  _questionFixe:
    - "T11_Q1"
    - "T11_Q2"
    - "T11_Q3"
    - "T11_Q4"
    - "T11_Q5"
include:
  - "https://raw.githubusercontent.com/Codeurfou-sys/Test-chat-bot-civique-/refs/heads/main/TEST11_QUESTIONS_ALEATOIRES.md"
---

# TEST 11 — Tirage aléatoire d’une question

Ce test compare deux mécanismes :

1. une variable **sans préfixe `_`**, réinterprétée à l’affichage ;
2. une variable **avec préfixe `_`**, tirée une seule fois au chargement du chatbot.

1. [🎲 Tester un nouveau tirage à chaque affichage](@{questionAleatoire})
2. [📌 Tester un tirage fixe pendant la session](@{_questionFixe})
3. [🧪 Ouvrir la page de contrôle](T11_CONTROLE)
