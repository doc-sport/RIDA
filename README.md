# RIDA

Deux applications autonomes, en un seul fichier HTML chacune, à ouvrir dans un navigateur
(ou à installer sur mobile depuis le navigateur). Toutes les données restent sur l'appareil,
dans le stockage local du navigateur.

## `index.html` — RIDA

Gestion des tâches et des notes : saisie clavier ou vocale, tri par thème et sous-thème,
priorités, RACI, minuteur, tableau de bord, synchronisation Google Drive, analyse de la
dictée par l'IA (clé API Anthropic saisie dans les réglages).

## `anglais.html` — LYRA

Apprentissage de l'anglais à partir de chansons et de poèmes.

1. **Textes** — coller les paroles, puis cliquer sur chaque mot inconnu pour l'ajouter au
   lexique ; sélectionner plusieurs mots pour saisir une expression ou faire expliquer une
   tournure. Traduction vers par vers et lecture à voix haute.
2. **Lexique** — une fiche par mot : prononciation, nature, traductions nuancées, pièges,
   collocations et exemples, le dernier exemple étant toujours le vers du texte d'origine.
   Fiches remplies par l'IA ou à la main.
3. **Quiz** — vocabulaire (sens, thème/version, phrase à trous, dictée, écoute) et grammaire,
   en répétition espacée (5 boîtes : 1, 3, 7 puis 21 jours), avec score, séries et
   progression.
4. **Grammaire** — chaque question sur une tournure donne une fiche explicative (structure,
   exemples, pièges) accompagnée de ses propres questions de quiz.
5. **Réglages** — clé API Anthropic, voix et débit de la synthèse vocale, longueur des
   séances, sauvegarde JSON et export CSV du lexique.

L'IA (Claude) est facultative : sans clé, tout reste utilisable en saisissant les fiches
soi-même.
