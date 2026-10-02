# Chicken Road 2 : journal des modifications et données ouvertes

**18+ — Contenu réservé aux adultes. Jeu responsable : fixez vos limites avant de commencer.**

Analyse technique indépendante des changements entre Chicken Road (v1) et Chicken Road 2, présentée comme un journal des modifications : chaque entrée est datée, sourcée et marquée selon son niveau de vérification. Les données brutes sont ouvertes pour vérification et réutilisation.

> **Chicken Road 2** est un jeu crash d'InOut Games : un multiplicateur monte pendant une traversée, vous encaissez avant le piège — ou vous perdez la mise. Le résultat de chaque tour est aléatoire (RNG).

## Méthode

Ce journal applique trois règles :

1. **Faits d'abord** — chaque entrée distingue le fait observé de l'interprétation.
2. **Niveau de vérification** — chaque entrée porte un label : ✅ Confirmé (au moins deux sources indépendantes) ou 🔍 À confirmer (une seule source ou signaux joueurs).
3. **Versionné** — ce journal évolue ; l'historique des corrections est tenu dans [CHANGELOG.md](CHANGELOG.md).

Sources consultées le 27/09/2026 : page studio InOut Games, fiche BetFury, vérification Casino.guru, signaux joueurs (forums publics, veille septembre 2026). Détail complet dans [METHODE.md](METHODE.md).

## Journal des modifications — v2.0 (15/04/2025)

### ➕ Ajouts

- **Quatre modes de difficulté** ✅ — Facile, Moyen, Difficile, Hardcore. La v1 n'en proposait aucun. Plus dur = plus de variance, pas plus de chances.
- **Multiplicateurs inférieurs à 1** ✅ — des tours peuvent créditer x0,7 ou x0,5 (observés sur sessions réelles) : le budget s'érode même quand « la poule avance ». Mécanique de conception, pas un bug.

### 🔄 Modifications

- **RTP annoncé : 98 % → 95,5 %** ✅ — Chicken Road 1 annonçait 98 %, Chicken Road 2 annonce 95,5 % (page studio, confirmé par BetFury). Rappel : un RTP est une moyenne sur des millions de tours, pas un engagement par session. La maison garde l'écart sur la durée — c'est mécanique, pas malveillant.

### ➖ Retraits

- **Aucun retrait documenté à ce jour** 🔍 — aucune suppression de fonctionnalité n'est attestée par les sources consultées. Cette section sera mise à jour si un retrait est confirmé.

### ⏸️ Inchangé

- **Éditeur** ✅ — InOut Games, comme la v1.
- **Principe crash** ✅ — mise, traversée, encaissement ou piège ; le RNG détermine chaque tour.
- **Accès navigateur** ✅ — aucune application officielle ; méfiez-vous des faux APK.
- **Prédiction impossible** ✅ — aucun outil ne prédit le résultat ; les produits « prediction » sont des arnaques.

## Données ouvertes

Le tableau comparatif brut est disponible en CSV : [data/comparaison-v1-v2.csv](data/comparaison-v1-v2.csv). Vous pouvez le réutiliser et le contester — c'est son but. La méthode de comparaison est publiée dans [METHODE.md](METHODE.md).

## Limites de l'analyse

- Ce journal repose sur les sources publiques disponibles ; le studio ne publie pas de notes de version détaillées.
- Les signaux joueurs (multiplicateurs < 1) viennent de discussions publiques, pas d'un audit indépendant du code.
- Les chiffres peuvent évoluer : vérifiez la date de la dernière mise à jour en tête du [CHANGELOG.md](CHANGELOG.md).

## Jeu responsable

Chicken Road 2 est un jeu d'argent : vous pouvez perdre votre mise, et sur la durée la maison gagne. Fixez un budget de perte maximum **avant** de jouer, décidez votre point d'encaissement **avant** le tour, et arrêtez-vous à la limite. 18+. Ne jouez jamais sous pression.

## FAQ

**Comment le journal des modifications est-il établi ?**
En croisant la page du studio, des fiches opérateurs et des signaux joueurs, avec au moins deux sources indépendantes pour le label « Confirmé ». Méthode complète dans METHODE.md.

**Puis-je réutiliser les données ouvertes ?**
Oui — le CSV est fait pour ça : vérification, visualisation, contestation. Citez la source.

**Que faire si je constate un changement non documenté ?**
Ouvrez une « issue » sur ce dépôt avec vos sources : si c'est vérifiable, le journal est mis à jour et versionné.

**Comment la neutralité de l'analyse est-elle garantie ?**
Publication indépendante, sans lien avec InOut Games. Divulgation : ce projet peut contenir des liens affiliés, sans effet sur les données publiées.

## Pour aller plus loin

- Hub complet (guides, analyses, jeu responsable) : https://chickenroadproductions.com/chicken-road-2/
- Comparatif détaillé v1 vs v2 : https://chickenroadproductions.com/chicken-road-2/ (section dédiée)
- Quel type de joueur êtes-vous ? https://chickenroadproductions.com/player-type/

---
*Chicken Road Productions — publication indépendante. 18+ · Jeu responsable.*
*Divulgation : certains liens peuvent être affiliés, sans surcoût pour vous et sans effet sur les données publiées.*
