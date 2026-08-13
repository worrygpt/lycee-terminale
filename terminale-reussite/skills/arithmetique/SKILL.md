---
name: arithmetique
description: Arithmétique en Maths Expertes (divisibilité, division euclidienne, congruences, PGCD, algorithme d'Euclide, théorèmes de Bézout, de Gauss et petit théorème de Fermat, nombres premiers). À utiliser pour tout exercice d'arithmétique - congruences, équations diophantiennes, critères de divisibilité, restes.
---

# Arithmétique (Maths Expertes)

## Rôle de Claude
Discipline de rigueur logique par excellence : exiger les définitions exactes et des raisonnements complets (les points se perdent sur les justifications). Faire pratiquer les tableaux de congruences.

## Divisibilité et division euclidienne
- a divise b (a | b) ⟺ il existe k ∈ ℤ tel que b = ka. Propriétés : a|b et b|c ⟹ a|c ; a|b et a|c ⟹ a | (ub + vc) (combinaisons linéaires — outil n°1).
- **Division euclidienne** de a par b > 0 : a = bq + r avec **0 ≤ r < b** (q, r uniques).

## Congruences
a ≡ b [n] ⟺ n | (a − b) ⟺ a et b ont le même reste modulo n.
**Compatibilité** : si a ≡ b et c ≡ d [n], alors a+c ≡ b+d, a−c ≡ b−d, ac ≡ bd, et aᵏ ≡ bᵏ [n].
⚠ **Pas de division** : ac ≡ bc [n] n'implique pas a ≡ b [n] (sauf si c est premier avec n).
Méthodes types : reste de 7¹⁰⁰ modulo 9 → chercher la **périodicité des puissances** (7¹≡7, 7²≡4, 7³≡1 [9] → période 3, 100 = 3×33+1 → reste 7) · critères de divisibilité · tableau exhaustif des restes possibles (x ≡ 0, 1, …, n−1) pour montrer qu'une équation n'a pas de solution.

## PGCD et algorithmes
- PGCD(a ; b) : plus grand diviseur commun. **Algorithme d'Euclide** : divisions euclidiennes successives, le PGCD est le dernier reste non nul. Propriété : PGCD(a ; b) = PGCD(b ; r).
- a et b **premiers entre eux** ⟺ PGCD = 1.

## Les trois théorèmes majeurs
- **Bézout** : PGCD(a ; b) = 1 ⟺ il existe u, v ∈ ℤ tels que au + bv = 1 (u, v par remontée de l'algorithme d'Euclide).
- **Gauss** : si a | bc et PGCD(a ; b) = 1, alors a | c. Corollaire : équations **diophantiennes** ax + by = c — solution particulière (Bézout) puis solution générale via Gauss.
- **Petit théorème de Fermat** : p premier ne divisant pas a ⟹ a^(p−1) ≡ 1 [p] (variante : aᵖ ≡ a [p] pour tout a).

## Nombres premiers
Définition (exactement deux diviseurs positifs) · il en existe une infinité (démonstration classique par l'absurde à connaître) · **décomposition en facteurs premiers** unique · test de primalité : diviseurs jusqu'à √n · applications au PGCD et au nombre de diviseurs.

## Pièges fréquents
Diviser une congruence · oublier 0 ≤ r < b · confondre « premiers entre eux » et « premiers » · Bézout dans le mauvais sens (au + bv = 1 ⟹ PGCD = 1 est vrai ; au + bv = d ⟹ PGCD = d est FAUX en général) · solutions diophantiennes non paramétrées en entiers relatifs · oublier la réciproque ou la conclusion.
